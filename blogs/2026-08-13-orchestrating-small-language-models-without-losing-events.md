---
title: "Orchestrating Small Language Models Without Losing Events or Context"
url: "https://dzone.com/articles/small-language-model-orchestration"
date: "2026-08-13"
author: "Akhil Madineni"
feed_url: "https://feeds.dzone.com/home"
---
Reliable orchestration for small language models depends less on model sophistication than on the durability of event flow and state. Under the assumptions used here — small model instances, little or no local state, Kafka as the event backbone, Temporal as the orchestration layer and durable state store, and Java as the runtime — the safest design is to treat model invocations as replayable side effects, Kafka as the transport and ordering substrate, and Temporal Workflow state as the canonical record of conversational progress. In that design, Kafka provides high-throughput append-only event
