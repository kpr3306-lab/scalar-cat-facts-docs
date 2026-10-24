# Cat Facts API documented with Scalar

Problem 11: API Documentation with Scalar (Introduction to Modern Application Development).

- `openapi.yaml`: hand-written OpenAPI 3.1 spec for https://catfact.ninja (/fact, /facts, /breeds)
- `docs.html`: Scalar API reference + built-in API client, loaded from the jsDelivr CDN
- `index.html`: project write-up (OpenAPI structure, how Scalar works, embedding, API client)

## Run
    python -m http.server 8000
Open http://localhost:8000 (write-up) and http://localhost:8000/docs.html (Scalar).
