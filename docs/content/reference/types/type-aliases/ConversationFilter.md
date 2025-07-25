[@slack/types](../index.md) / ConversationFilter

# Type Alias: ConversationFilter

```ts
type ConversationFilter = 
  | BaseConversationFilter & Required<Pick<BaseConversationFilter, "include">>
  | BaseConversationFilter & Required<Pick<BaseConversationFilter, "exclude_bot_users">>
| BaseConversationFilter & Required<Pick<BaseConversationFilter, "exclude_external_shared_channels">>;
```

Defined in: [block-kit/composition-objects.ts:199](https://github.com/slackapi/node-slack-sdk/blob/main/packages/types/src/block-kit/composition-objects.ts#L199)

## Description

Defines a filter for the list of options in a conversation selector menu. The menu can be either a
conversations select menu or a conversations multi-select menu.

## See

[Conversation filter object reference](https://docs.slack.dev/reference/block-kit/composition-objects/conversation-filter-object).
