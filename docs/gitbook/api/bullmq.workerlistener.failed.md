<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bullmq](./bullmq.md) &gt; [WorkerListener](./bullmq.workerlistener.md) &gt; [failed](./bullmq.workerlistener.failed.md)

## WorkerListener.failed property

Listen to 'failed' event.

This event is triggered when a job has thrown an exception.

<b>Signature:</b>

```typescript
failed: (job: Job, error: Error, prev: string) => void;
```