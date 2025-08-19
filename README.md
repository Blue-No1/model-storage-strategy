# Model Storage Strategy

Notes & comparisons on where to store large open-weight LLMs.  
Ghi chú & so sánh các phương án lưu trữ mô hình open-weight dung lượng lớn.

> ⚠️ Work in progress / Đang trong quá trình nghiên cứu

## Options
- **Local NVMe**: fastest but limited capacity, no scalability.
- **Google Cloud Storage (GCS)**: good for Vertex AI integration, per-GB cost.
- **Amazon S3**: widely supported, ecosystem mature.
- **Hugging Face Hub**: free hosting for smaller repos, community-friendly.

## Progress Log
- **[YYYY-MM-DD]** Init repo.
- **[YYYY-MM-DD]** Added cost comparison notes.
