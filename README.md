# Segments.ai (segments-ai)

Segments.ai is a data-labeling platform for computer vision, supporting 2D image segmentation and vectors as well as 3D point cloud and multi-sensor fusion annotation. Its REST API and Python SDK let teams manage datasets, samples, labels, labelsets, and versioned releases programmatically for building training data pipelines.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/segments-ai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/segments-ai/refs/heads/main/apis.yml)

## Tags

- Data Labeling
- Computer Vision
- Point Cloud
- Annotation
- Machine Learning

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Segments.ai Datasets API

Create, list, retrieve, update, and delete labeling datasets, including their task type (image segmentation, vectors, point cloud cuboid/segmentation, multi-sensor fusion), categories, task attributes, and collaborators.

- **Human URL:** [https://docs.segments.ai/reference/api](https://docs.segments.ai/reference/api)
- **Base URL:** `https://api.segments.ai`

#### Tags

- Datasets
- Projects
- Computer Vision

#### Properties

- [Documentation](https://docs.segments.ai/background/main-concepts)
- [API Reference](https://docs.segments.ai/reference/api)
- [OpenAPI](openapi/segments-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/segments-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/segments-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/segments-ai/segments-ai)

### Segments.ai Samples API

Manage the individual items to be labeled within a dataset - images, point clouds, and multi-sensor sequences - with attributes, metadata, and labeling priority.

- **Human URL:** [https://docs.segments.ai/reference/api](https://docs.segments.ai/reference/api)
- **Base URL:** `https://api.segments.ai`

#### Tags

- Samples
- Assets
- Images
- Point Clouds

#### Properties

- [Documentation](https://docs.segments.ai/background/main-concepts)
- [API Reference](https://docs.segments.ai/reference/api)
- [OpenAPI](openapi/segments-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/segments-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/segments-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Segments.ai Labels API

Create, retrieve, update, and delete the annotation labels attached to a sample for a given labelset, with label status (LABELED, REVIEWED, REJECTED, PRELABELED, SKIPPED), attributes, and model score.

- **Human URL:** [https://docs.segments.ai/reference/api](https://docs.segments.ai/reference/api)
- **Base URL:** `https://api.segments.ai`

#### Tags

- Labels
- Annotations
- Ground Truth

#### Properties

- [Documentation](https://docs.segments.ai/background/main-concepts)
- [API Reference](https://docs.segments.ai/reference/api)
- [OpenAPI](openapi/segments-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/segments-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/segments-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Segments.ai Labelsets API

Manage labelsets within a dataset - named groups of labels such as ground-truth or model predictions - allowing multiple parallel annotation sets per sample.

- **Human URL:** [https://docs.segments.ai/reference/api](https://docs.segments.ai/reference/api)
- **Base URL:** `https://api.segments.ai`

#### Tags

- Labelsets
- Predictions
- Ground Truth

#### Properties

- [Documentation](https://docs.segments.ai/background/main-concepts)
- [API Reference](https://docs.segments.ai/reference/api)
- [OpenAPI](openapi/segments-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/segments-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/segments-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Segments.ai Releases API

Create, list, retrieve, and delete versioned, immutable snapshots of a dataset's labels for export and reproducible ML training.

- **Human URL:** [https://docs.segments.ai/reference/api](https://docs.segments.ai/reference/api)
- **Base URL:** `https://api.segments.ai`

#### Tags

- Releases
- Versioning
- Export

#### Properties

- [Documentation](https://docs.segments.ai/background/main-concepts)
- [API Reference](https://docs.segments.ai/reference/api)
- [OpenAPI](openapi/segments-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/segments-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/segments-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/segments-ai)
- [LinkedIn](https://www.linkedin.com/company/segments-ai)
- [Website](https://segments.ai)
- [Documentation](https://docs.segments.ai)
- [Plans](plans/segments-ai-plans-pricing.yml)
- [Rate Limits](rate-limits/segments-ai-rate-limits.yml)
- [Fin Ops](finops/segments-ai-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
