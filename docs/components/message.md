---
title: Message
lang: en-US
---

# Message

Commonly used `Message`.
We will provide some themes color like `success`, `warning`, `error` ,`info`,`primary` and `secondary` for you.

## Basic usage

if you want get theme , you can use `message.[option]` or provide `type` to options ; Use `content` to define Message's content.

<demo src="../example/message/basic.vue"></demo>

## Closable

Use `closable` to show close icon and close message

<demo src="../example/message/closable.vue"></demo>

## Icon

Use `icon` to show icon before content
<demo src="../example/message/icon.vue"></demo>

## Duration 

Use `duration` to control the `message` components display time. the defaultValue is `5000 ms`

<demo src="../example/message/duration.vue"></demo>



## Message Attributes

| Attribute         | Description   | Type    | Accepted Values         | Default |
| ----------------- | --------------------------------------------------------------- | -------------------------------------- | ------------------------------------------------------------- | ------- |
| type              | theme | String  |  primary / secondary / success / warning / error / info    | primary      |
| content           | message content| String |  -    | ''      |
| closable          | show closable | Boolean |  true/false    | false      |
| icon              | content icon| String |  -    | '' |



## Message methods 

| Event Name       | Parameters                                                                                      | Description                              |
|------------------|-------------------------------------------------------------------------------------------------|------------------------------------------|
| close           | void  | triggers when the message was closed  |