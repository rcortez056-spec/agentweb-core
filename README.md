# AgentWeb Core

A static browser page that loads an agent-network JSON file and displays its status. The multi-agent runtime described below is planned, not built.

## What it does

AgentWeb Core is a browser-side concept for agent networks. The live page loads a JSON agent-network file (`agent-network.json`) and displays its status. Multi-agent execution and peer discovery are planned.

## How we built it

A static HTML page with JavaScript, deployed on Vercel. The page loads a JSON agent-network file in the browser. No server backend.

## Challenges we ran into

Deciding how flexible the JSON spec should be for different agents, and how to keep it separate from the runtime that will eventually run it.

## Accomplishments

A working static page that loads and displays a JSON agent-network file.

## What we learned

Keeping the agent spec separate from the runtime is a useful starting point for a browser-native agent network.

## What's next

Build the multi-agent execution loop and peer discovery described above.

## Built with

HTML, JavaScript, JSON, Vercel

## Try it out

- Live page: https://agentweb-core.vercel.app
- GitHub: https://github.com/rcortez056-spec/agentweb-core
