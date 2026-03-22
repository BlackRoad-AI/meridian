# Meridian — TODO

## [RC] Core Orchestration
- [ ] [RC] Build task decomposition engine with dependency DAG
- [ ] [RC] Implement agent capability registry and matching
- [ ] [RC] Build parallel execution manager with git worktree isolation
- [ ] [RC] Implement agent health monitoring and failover
- [ ] [RC] Add priority queue with dynamic rebalancing

## [RC] Conflict Resolution
- [ ] [RC] Build three-way merge engine using Tree-sitter AST
- [ ] [RC] Implement scope boundary enforcement per agent
- [ ] [RC] Add semantic conflict detection (beyond text diff)
- [ ] [RC] Build escalation protocol for unresolvable conflicts
- [ ] [RC] Implement merge preview with dry-run mode

## [RC] Memory & Communication
- [ ] [RC] Build shared SQLite memory store with FTS5 search
- [ ] [RC] Implement NATS pub/sub for real-time agent messaging
- [ ] [RC] Build handoff protocol with context packaging
- [ ] [RC] Add codex integration for cross-agent solution sharing
- [ ] [RC] Implement TIL broadcast system for agent learnings

## [RC] Agent Integration
- [ ] [RC] Build Claude agent adapter (Anthropic API + local)
- [ ] [RC] Build GPT agent adapter (OpenAI API)
- [ ] [RC] Build Ollama local agent adapter
- [ ] [RC] Implement custom agent plugin interface
- [ ] [RC] Add agent rate limiting and quota management

## [RC] Dashboard & Monitoring
- [ ] [RC] Build real-time web dashboard with WebSocket updates
- [ ] [RC] Implement progress tracking with ETA estimation
- [ ] [RC] Add conflict resolution log viewer
- [ ] [RC] Build agent performance analytics
- [ ] [RC] Implement alerting for stuck/failed tasks

## [RC] Distribution
- [ ] [RC] Package as pip installable module
- [ ] [RC] Build Docker Compose deployment
- [ ] [RC] Create Homebrew formula
- [ ] [RC] Write quickstart guide with examples
- [ ] [RC] Build CI/CD pipeline for releases
