<p align="center">
  <img src="https://github.com/RYASTRA.png?size=160" width="120" alt="RYASTRA logo">
</p>

<h1 align="center">RYASTRA</h1>

<p align="center">
  <strong>Open-source systems that turn public space data into tools people can actually use.</strong>
</p>

<p align="center">
  NASA data &nbsp;·&nbsp; satellite signals &nbsp;·&nbsp; developer tools
</p>

<p align="center">
  <a href="https://ryastra.github.io/nasa-observatory/">Explore NASA Observatory</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/RYASTRA/satnogs-dashboard">Run the SatNOGS workbench</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/RYASTRA/nasa-mcp">Connect to NASA APIs</a>
</p>

RYASTRA builds focused software around open space data—from live monitors and
searchable research archives to satellite signal analysis and agent-ready APIs.
The projects favor transparent pipelines, reproducible results, small deployment
footprints, and clear limits.

## Start here

| Project | What it does |
| --- | --- |
| [**NASA Observatory**](https://ryastra.github.io/nasa-observatory/) | One live view across space weather, planetary defense, exoplanet discoveries, NASA technology, and space-biology updates. |
| [**SatNOGS Review Workbench**](https://github.com/RYASTRA/satnogs-dashboard) | A self-hosted, read-only observation-review queue combining signal triage, Doppler identification, and decoder evidence. |
| [**NASA MCP**](https://github.com/RYASTRA/nasa-mcp) | All 16 of NASA's public APIs as MCP tools through one FastMCP server and Docker setup. |

## NASA data

| Project | Focus |
| --- | --- |
| [`nasa-observatory`](https://github.com/RYASTRA/nasa-observatory) | Live overview of the NASA data fleet. |
| [`nasa-space-weather`](https://github.com/RYASTRA/nasa-space-weather) | Plain-English watch for solar flares, CMEs, and geomagnetic storms. |
| [`nasa-defense`](https://github.com/RYASTRA/nasa-defense) | Impact risks, close approaches, fireballs, and the Apophis 2029 countdown. |
| [`nasa-new-worlds`](https://github.com/RYASTRA/nasa-new-worlds) | Weekly watch for new exoplanet confirmations, retractions, and standout worlds. |
| [`nasa-tech-explorer`](https://github.com/RYASTRA/nasa-tech-explorer) | Searchable mirror of NASA patents, software, and spinoffs. |
| [`nasa-space-biology`](https://github.com/RYASTRA/nasa-space-biology) | Faceted explorer for NASA OSDR space-biology studies. |
| [`nasa-mcp`](https://github.com/RYASTRA/nasa-mcp) | NASA's public API catalog exposed through MCP. |

## SatNOGS tooling

| Project | Focus |
| --- | --- |
| [`satnogs-dashboard`](https://github.com/RYASTRA/satnogs-dashboard) | One observation-review workflow across the analysis tools. |
| [`satnogs-signal`](https://github.com/RYASTRA/satnogs-signal) | ML-assisted signal-versus-noise triage for waterfall images. |
| [`satnogs-id`](https://github.com/RYASTRA/satnogs-id) | Doppler-based identification of similar CubeSats. |
| [`satnogs-decoder`](https://github.com/RYASTRA/satnogs-decoder) | Generation and validation of Kaitai Struct telemetry decoders. |

## How we build

- **Useful first.** Public data should lead to a working interface, not another
  integration project.
- **Inspectable by default.** Sources, evidence, assumptions, and limitations
  belong close to the result.
- **Operationally small.** Projects favor static sites, GitHub Actions, and
  Docker over infrastructure that needs constant care.
- **Human judgment stays in the loop.** Models support review where uncertainty
  matters; they do not hide it.

## Contributing

Bug reports, data corrections, validation results, feature ideas, and pull
requests are welcome. Open an issue in the project closest to your interest;
each repository includes its own setup and scope.

All current RYASTRA projects are open source under the MIT License.

---

<sub>RYASTRA is an independent open-source organization. It is not affiliated
with or endorsed by NASA, JPL, SatNOGS, or the Libre Space Foundation. Each
project documents its upstream data and software.</sub>
