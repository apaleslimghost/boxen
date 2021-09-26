# Snapshot report for `tests/title-option.js`

The actual snapshot is saved in `title-option.js.snap`.

Generated by [AVA](https://avajs.dev).

## title option works

> Snapshot 1

    `┌ title ┐␊
    │foo    │␊
    └───────┘`

## title align left

> Snapshot 1

    `┌ title ────────┐␊
    │foo bar foo bar│␊
    └───────────────┘`

## title align center

> Snapshot 1

    `┌──── title ────┐␊
    │foo bar foo bar│␊
    └───────────────┘`

## title align right

> Snapshot 1

    `┌──────── title ┐␊
    │foo bar foo bar│␊
    └───────────────┘`

## long title expands box

> Snapshot 1

    `┌ very long title ┐␊
    │foo              │␊
    └─────────────────┘`