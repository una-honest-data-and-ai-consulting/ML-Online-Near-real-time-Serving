# Hands-on with ML serving pipelines

## Online serving near real-time

Online inference is definitely more challenging than batch inference. Why? Due to the latency restrictions on our systems.

**Online inference** is about responding with a prediction to the request of the end user with a low latency.

**What to optimize**: latency

**End user**: usually interacts with a model directly available through an API

**Validation**: offline and online via A/B testing
