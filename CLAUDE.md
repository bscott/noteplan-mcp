# NotePlan MCP Server - Claude Memory

## Commands
- Start the server: `npm start`
- Development mode with auto-restart: `npm run dev`
- Run tests: `npm test`
- Lint code: `npm run lint`

## Project Structure
- `/src` - Main source code
- `/tests` - Test files

## MCP Protocol Info
The Message Control Protocol (MCP) server enables Claude to interact with NotePlan through a standardized interface. The main endpoint is `/mcp/v1/command` which accepts commands like `ping` and `getNotes`.

## Code Style Preferences
- 2-space indentation
- Single quotes for strings
- Semicolons required
- Unix line endings