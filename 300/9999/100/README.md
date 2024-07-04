# 100 - For Web based NotePlan (recommended)

Based on "How to add links to websites?" at https://help.noteplan.co/article/168-how-to-add-links-to-websites

Based on "n8n public REST API" at https://docs.n8n.io/api/

Based on "How to build an API with n8n: a comprehensive tutorial" at https://blog.n8n.io/how-to-build-api/

## 100 - Create a Link in Web based NotePlan

Simply copy a URL (here: ```https://google.com```) to your clipboard, then paste it into a note of NotePlan. You can hoover over the link to edit it, open it in a new tab (default) or remove it.

```
https://google.com
```

![create-a-link-001](https://github.com/vanHeemstraSystems/noteplan/assets/1499433/3e2adbd7-2f66-405b-8075-b9ccd286a127)

## 200 - Create a Trigger in n8n to be called from Web based NotePlan

Based on "n8n Form Trigger" at https://docs.n8n.io/integrations/builtin/core-nodes/n8n-nodes-base.formtrigger/

Based on n8n Webhook" as described in the book "Rapid Product Development with n8n" by Jason McFeetors & Tanay Pant

**NOTE**: Instead of a Form, we create a Web Hook in n8n.

The Webhook node is a trigger node that executes a workflow when it receives a remote connection. It collects the information that it receives and performs actions based on that information.

MORE
