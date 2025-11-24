```
ecp-grid-gateway/
├─ README.md
├─ LICENSE-ECP.txt
├─ schemas/
│  ├─ ecp_token.schema.json
│  ├─ ecp_gateway_request.schema.json
│  ├─ ecp_response.schema.json
│  ├─ ecp_audit_record.schema.json
│  ├─ ecp_kye_validation.schema.json
│  ├─ ecp_compliance_check.schema.json
│  ├─ ecp_filter_result.schema.json
│  ├─ ecp_connector_operation.schema.json
│  ├─ ecp_processing_event.schema.json
│  ├─ ecp_report.schema.json
│  ├─ policy_snapshot.schema.json
│  ├─ trust_registry_entry.schema.json
│  ├─ sovereign_routing_decision.schema.json
│  ├─ ecp_manifest.schema.json
│  └─ ecp_intent_declaration.schema.json
├─ docs/
│  ├─ architecture.md
│  ├─ dataflow.md
│  ├─ glossary.md
│  ├─ mermaid/
│  │  ├─ global-ecosystem.mmd
│  │  ├─ runtime-plane.mmd
│  │  └─ request-lifecycle.mmd
│  └─ api.md
├─ python-fastapi/
│  ├─ pyproject.toml
│  ├─ uvicorn.ini
│  └─ app/
│     ├─ __init__.py
│     ├─ main.py
│     ├─ config.py
│     ├─ core/
│     │  ├─ canonical.py
│     │  ├─ hashing.py
│     │  └─ signing.py
│     ├─ models.py
│     ├─ db.py
│     ├─ schemas/
│     │  ├─ ecp_gateway_request.py
│     │  └─ ecp_response.py
│     ├─ services/
│     │  ├─ token_validator.py
│     │  ├─ kye_engine.py
│     │  ├─ compliance_engine.py
│     │  ├─ filters_engine.py
│     │  ├─ routing_engine.py
│     │  ├─ processing_engine.py
│     │  └─ audit_logger.py
│     └─ api/
│        ├─ gateway.py
│        └─ health.py
└─ typescript-nestjs/
   ├─ package.json
   ├─ tsconfig.json
   ├─ nest-cli.json
   └─ src/
      ├─ main.ts
      ├─ app.module.ts
      ├─ config/
      │  └─ config.ts
      ├─ core/
      │  ├─ canonical.ts
      │  ├─ hashing.ts
      │  └─ signing.ts
      ├─ gateway/
      │  ├─ gateway.module.ts
      │  ├─ gateway.controller.ts
      │  └─ dto/
      │     ├─ ecp-gateway-request.dto.ts
      │     └─ ecp-response.dto.ts
      ├─ services/
      │  ├─ token-validator.service.ts
      │  ├─ kye.service.ts
      │  ├─ compliance.service.ts
      │  ├─ filters.service.ts
      │  ├─ routing.service.ts
      │  ├─ processing.service.ts
      │  └─ audit.service.ts
      └─ common/
         └─ types.ts
```
