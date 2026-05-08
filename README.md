# SwarmSim

> **Working title.** Name subject to change.

An open-source simulation environment for multi-agent robotic systems — swarms, flocks, and clusters of autonomous vehicles operating in realistic physical environments.

## Vision

SwarmSim is a distributed, event-sourced simulation kernel for developing and testing coordinated autonomous systems. Rather than extending a game engine, SwarmSim treats the simulation fabric as the core and delegates rendering and physics to an open-source 3D engine as a presentation layer.

- **Simulation kernel**: Event-sourced world foundation with nanosecond-precision temporal modeling, built on distributed systems patterns
- **Agents**: Individual and collective agent models operating as independent services with low-level device control
- **Sensing & actuation**: Unified signal propagation framework covering sensors, actuators, and communication channels (including optical/LiFi)
- **Extensibility**: Distributed architecture with service and schema versioning, hook APIs, and plugin points

## Future Directions

- Geospatial terrain import and environmental condition modeling
- Computational fluid dynamics integration (aerial and underwater vehicles)
- SDK, scenario tooling, observability, and training gym integration

## Status

**Pre-development.** Defining architecture and evaluating open-source 3D engines.

## License

[GNU Lesser General Public License v3.0](LICENSE)
