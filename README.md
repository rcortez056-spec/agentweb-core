# AgentWeb Core

A static browser page that displays a sample agent-network spec. The multi-agent runtime described here is planned, not built.

## Inspiration

Web apps today depend heavily on server round-trips, and agents struggle to find and share state across separate sites. We wanted to explore a browser-native agent network, with agent capabilities described in a plain JSON file, as a starting point for the Open Agentic Web Challenge.

## What it does

AgentWeb Core is a browser-side concept for agent networks. The live page displays a sample agent-network spec defined in the page's code. Multi-agent execution and peer discovery are planned.

## How we built it

A static HTML page with JavaScript, deployed on Vercel. No server backend.

## Challenges we ran into

Deciding how flexible the agent spec should be for different agents, and how to keep it separate from the runtime that will eventually run it.

## Accomplishments

A working static page that displays an agent-network spec.

## What we learned

Keeping the agent spec separate from the runtime is a useful starting point for a browser-native agent network.

## What's next

Build the multi-agent execution loop and peer discovery described above.

## Built with

HTML, JavaScript, JSON, Vercel

## Try it out

- Live page: https://agentweb-core.vercel.app
- GitHub: https://github.com/rcortez056-spec/agentweb-core
