# Writing procedural steps: a style guide

Procedures are the most-used part of any product documentation. Users follow them with the product open in front of them, often under time pressure. This guide covers the rules I follow so every procedure reads the same way, no matter who wrote it.

## Before you write

Answer three questions first:

1. **Who is doing this task?** Name the role and any permissions required.
2. **What do they have when they finish?** Write the result before you write the steps.
3. **What must be true before they start?** List prerequisites so users do not fail halfway through.

## Rules for each step

| Rule | Do | Don't |
| --- | --- | --- |
| One action per step | Select **Save**. | Select **Save** and then close the form and refresh the list. |
| Start with a verb | Enter the incident number. | The incident number should be entered. |
| Say where before what | In the **Table** field, select **Incident**. | Select **Incident** in the field called Table. |
| Bold UI labels exactly as shown | Select **Build flow**. | Select the build flow button. |
| Put optional steps last in the step | To filter the list, select **Filter**. (Optional) | Optionally, if you want, you can filter. |

## Use the right verb

| Interface element | Verb |
| --- | --- |
| Button, link, tab, menu item, check box | Select |
| Text field | Enter |
| Dropdown or list | Select |
| Drag and drop | Drag |
| Key on the keyboard | Press |

Use **select** instead of *click* so the same instruction works on a mouse, a keyboard, and a touch screen.

## Results, not suspense

Add a step result only when the screen changes in a way the user might not expect. If nothing visible happens, the user may think the step failed, so tell them what to look for:

> Select **Activate**. The flow status changes to **Active**.

## Keep procedures short

- Aim for 3 to 10 steps.
- If a procedure needs more than 10 steps, split it into two tasks and link them.
- Use substeps for a short group of actions inside one step, never more than one level deep.

## Check before you publish

- [ ] Every step starts with a verb.
- [ ] Every UI label matches the product exactly, including capitalization.
- [ ] Prerequisites and required roles appear before step 1.
- [ ] The final result is stated.
- [ ] I tested every step in a live instance.
