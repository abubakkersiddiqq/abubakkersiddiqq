
<div align="center">

```
 █████╗ ██████╗ ██╗   ██╗██████╗  █████╗ ██╗  ██╗██╗  ██╗███████╗██████╗
██╔══██╗██╔══██╗██║   ██║██╔══██╗██╔══██╗██║ ██╔╝██║ ██╔╝██╔════╝██╔══██╗
███████║██████╔╝██║   ██║██████╔╝███████║█████╔╝ █████╔╝ █████╗  ██████╔╝
██╔══██║██╔══██╗██║   ██║██╔══██╗██╔══██║██╔═██╗ ██╔═██╗ ██╔══╝  ██╔══██╗
██║  ██║██████╔╝╚██████╔╝██████╔╝██║  ██║██║  ██╗██║  ██╗███████╗██║  ██║
╚═╝  ╚═╝╚═════╝  ╚═════╝ ╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝
```

</div>

```bash
$ whoami
> Abubakker Siddiq
> Python Backend Engineer  |  AI Integration
> Bengaluru, IN  |  Open to opportunities
```

---

## `cat /proc/about`

I build backend systems that talk to AI.  
Not wrappers — actual production services with RAG pipelines, async APIs, and deployments that survive cold starts.

Currently in my final year of BCA at East Point College, with a backend internship at Zephyr Technologies behind me and three live projects on Render.

```python
class AbubakerSiddiq:
    role     = "Python Backend Engineer"
    focus    = "AI-integrated APIs"
    location = "Bengaluru, IN"
    learning = ["RAG systems", "pytest patterns", "system design"]
    open_to  = "small startups (5-30 people) moving fast on real problems"
```

---

## `ls -la ~/projects/`

```
drwxr-xr-x  bino/           Go + OpenRouter  |  dynamic LLM routing + fallback    |  live
drwxr-xr-x  blogflow-api/   FastAPI + PostgreSQL + JWT + Docker + Supabase         |  live
drwxr-xr-x  deep-reader/    FastAPI + RAG + pgvector + Docker + Render             |  live
```

---

### `cat ~/projects/bino/README`

**LLM API Gateway** — built in Go, routes requests across 10+ models via OpenRouter with a hardcoded fallback array so the service never goes dark when a model is unavailable. Dynamic model selection based on request context.

`[Go]` `[OpenRouter API]` `[REST]` `[Render]`
&nbsp;&nbsp; → **[Live](https://bino-smart-query-helper.onrender.com)** &nbsp;|&nbsp; **[Source](https://github.com/abubakkersiddiqq/bino_smart_query_helper)**

---

### `cat ~/projects/blogflow-api/README`

**Production Blog REST API** — async FastAPI service with JWT auth, role-based access, and full CRUD. Resolved real production issues: `asyncpg` prepared statement conflicts fixed via `statement_cache_size: 0`, Supabase IPv6 incompatibility solved by switching to Session Pooler, cold-start latency handled with UptimeRobot on `/health`.

`[FastAPI]` `[PostgreSQL]` `[async SQLAlchemy]` `[Pydantic v2]` `[Docker]` `[Supabase]` `[JWT]`
&nbsp;&nbsp; → **[Live](https://real-blog.onrender.com)** &nbsp;|&nbsp; **[Source](https://github.com/abubakkersiddiqq/real-blog)**

---

### `cat ~/projects/deep-reader/README`

**AI Document Reader** — FastAPI service that ingests documents and answers questions over them using a RAG pipeline with vector similarity search. Containerized with Docker and deployed on Render.

`[FastAPI]` `[RAG]` `[pgvector]` `[embeddings]` `[Docker]` `[Render]`
&nbsp;&nbsp; → **[Live](https://deepreader.onrender.com/)** &nbsp;|&nbsp; **[Source](https://github.com/abubakkersiddiqq/deep-reader)**

---

## `stack --list`

```
language    Python (primary)  |  Go
framework   FastAPI  |  SQLAlchemy (async)  |  Pydantic v2
AI/ML       RAG pipelines  |  vector embeddings  |  OpenRouter
database    PostgreSQL  |  pgvector  |  Supabase
infra       Docker  |  Render  |  JWT  |  UptimeRobot
testing     pytest
tools       Git  |  Postman
```

---

## `ping --connect`

```bash
$ curl -X GET https://links.abubakker.dev

{
  "github":   "https://github.com/abubakkersiddiqq",
  "linkedin": "https://www.linkedin.com/in/abubakker-siddiq-715759231/",
  "email":    "abubakkerconnect@gmail.com"
}
```

---

## `tail -f /var/log/activity.log`

```
[2026-01]  Deployed bino (Go LLM gateway) to Render
[2026-02]  Deployed BlogFlow API — resolved Supabase + asyncpg production issues
[2026-03]  Completed backend internship @ Zephyr Technologies
[2026-04]  Shipped DeepReader — RAG document service, pgvector + Docker + Render
```

---

<div align="center">

```
# python backend  |  ai integration  |  open to hire
# if you're building something real — let's talk
```

</div>
