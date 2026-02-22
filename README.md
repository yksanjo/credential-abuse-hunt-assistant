# Credential Abuse Hunt Assistant

Detect likely credential stuffing and session hijack chains.

## Priority Metadata

- ID: 104
- Domain: security-agent
- TTE (days): 3
- Exposure score: 8/10
- Wave: 1
- Priority score: 7.60

## Phase-1 Build

1. Risk/exposure assessment API.
2. Deterministic launch planning endpoint.
3. Domain-tailored threat and rollout docs.
4. CI test gate and local runnable service.
5. Spatial 3D starter (for spatial projects).

## Run

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -e .[dev]
make test
make run
```
