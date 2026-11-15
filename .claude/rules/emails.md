---
paths:
  - "campaigns/**/emails/*.md"
---

# Rules for email files

These rules apply to every email file in any campaign. Each email file must follow all of them.

## Top of the file

- The first line starts with `Subject: ` and is 50 characters or fewer in total.
- The second line starts with `Preview: ` and is 90 characters or fewer in total.

- Each file has one subject only. Put alternative subject lines for tests in `notes/`.

## Greeting

- Greet the reader with `{{first_name}}`, for example "Hello {{first_name}},".

## Link

- Use exactly one main link, written like this: `[Button text](https://riseandcrumb.example/spring)`
- Do not add other links in the body.

## Ending

End the file with these parts, in this order:

1. Our sign-off from `brand/voice.md`: the closing line, then `Rise & Crumb` on its own line. Use `Fresh from the oven,` in every email of a campaign.
2. This two-line footer as plain text. Do not put it inside a code block.

```
You're getting this because you joined the Rise & Crumb list.
Rise & Crumb, {{company_address}} · Unsubscribe: {{unsubscribe_url}}
```

(The box above only shows the footer for this rule file. In an email file, write the two lines as plain text.)
