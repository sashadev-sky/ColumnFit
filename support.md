---
title: ColumnFit Support
---

# ColumnFit Support

## How to use

1. Select one or more columns (Ctrl-click / Cmd-click for non-adjacent columns).
2. Open Extensions → ColumnFit → Fit rows to selected columns.
3. Rows resize to fit the wrapped text of the selected columns only.

## Requirements

The selected columns must use Wrap text formatting. Clip or Overflow columns render as one line, so nothing can make them taller.

## Common questions

**Rows are slightly too short or too tall.**
Heights are estimated from font metrics, since Google Sheets exposes no per-column auto-fit. Re-run after adjusting column width, or use "Set fixed height" for a uniform result.

**Rows stopped auto-growing when I edit.**
ColumnFit pins row heights. Edit your content, then run it again.

**Which columns count?**
Only the selected ones. Other columns keep their content but no longer dictate row height.

**Can I undo?**
Yes. Ctrl+Z / Cmd+Z reverts the row height change like any other edit.

## Report an issue

columnfit-support@googlegroups.com

## Draft tester opt-out

If you were added as a draft tester and no longer want early access, fill out the ColumnFit Draft Tester Opt-Out form [here](https://forms.gle/5fvLmWC8kBh6u1Ym7) and you will be removed within two business days.

[Home](./) · [Privacy Policy](privacy) · [Terms of Service](terms)
