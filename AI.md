---
name: ww-input-range
description: >-
  The `ww-input-range` component provides a customizable range input slider that
  allows users to select a value within a specified range, featuring optional
  tooltips to display the current value and various styling options for enhanced
  visual presentation.
keywords:
  - range input
  - slider component
  - numeric value input
  - tooltip display
  - customizable styles
  - min-max range
  - step value
  - active range background
  - selector styling
  - tooltip styling
---

#### ww-input-range

1. **Component Purpose:** This component renders a range input, allowing the user to select a value within a specified range by dragging a slider or entering a numeric value. It can display a tooltip showing the current value.

2. **Properties:**
   - `value`: `number` - Initial value of the range input. Default: `0`.
   - `required`: `boolean` - Whether the range input is required. Default: `true`.
   - `min`: `number` - Minimum value of the range (between 0 and 1000). Default: `0`.
   - `max`: `number` - Maximum value of the range (between 1 and 1000). Default: `100`.
   - `step`: `number` - Step value for the range (between 1 and 100). Default: `1`.
   - `isTooltip`: `boolean` - Whether to display a tooltip with the current value. Default: `true`.
   - `globalStyle`: `object` - Global styles for the component.
     - `fontSize`: `string` (e.g., `"15px"`, `"2em"`, `"1.5rem"`) - Font size of the tooltip text.
     - `fontFamily`: `string` - Font family of the tooltip text.
     - `useActiveRangeBackground`: `boolean` - Whether to use a different background color for the active range. Default: `false`.
     - `rangeBackgroundColor`: `string` - Background color of the range. Default: `"rgb(9, 154, 242)"`.
     - `activeRangeBackgroundColor`: `string` - Background color of the active range (if `useActiveRangeBackground` is true). Default: `null`.
     - `selectorBorderColor`: `string` - Border color of the range selector. Default: `"#1565C0"`.
     - `selectorBackgroundColor`: `string` - Background color of the range selector. Default: `"rgb(9, 154, 242)"`.
     - `tooltipBackground`: `string` - Background color of the tooltip. Default: `"rgb(9, 154, 242)"`.
     - `tooltipTextColor`: `string` - Text color of the tooltip. Default: `"#FFFFFF"`.

3. **Children Components:** This component does not support any child components.