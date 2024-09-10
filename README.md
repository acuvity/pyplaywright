# pyplaywright

## Install 

```bash
pip install pyplaywright
```

## Using the tracer 

```
from pyplaywright.websocket.tracer import WebsocketTracer
```

## Create an instance of Websocket Tracer 

```bash
# Listen to all WebSocket events
wt = WebsocketTracer(page)
```

## Storing to output file

```bash
wt.write("trace.jsonl")
```
