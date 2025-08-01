---
title: baseline-shift
slug: Web/SVG/Reference/Attribute/baseline-shift
page-type: svg-attribute
browser-compat: svg.global_attributes.baseline-shift
sidebar: svgref
---

The **`baseline-shift`** attribute allows repositioning of the dominant-baseline relative to the dominant-baseline of the parent text content element. The shifted object might be a sub- or superscript.

> [!NOTE]
> As a presentation attribute, `baseline-shift` also has a CSS property counterpart: {{cssxref("baseline-shift")}}. When both are specified, the CSS property takes priority.

> [!NOTE]
> This property is going to be deprecated and authors are advised to use [`vertical-align`](/en-US/docs/Web/CSS/vertical-align) instead.

You can use this attribute with the following SVG elements:

- {{SVGElement("textPath")}}
- {{SVGElement("tspan")}}

## Usage notes

<table class="properties">
  <tbody>
    <tr>
      <th scope="row">Value</th>
      <td>
        {{cssxref("length-percentage")}} | <code>sub</code> |
        <code>super</code>
      </td>
    </tr>
    <tr>
      <th scope="row">Default value</th>
      <td><code>0</code></td>
    </tr>
    <tr>
      <th scope="row">Animatable</th>
      <td>Yes</td>
    </tr>
  </tbody>
</table>

- `sub`
  - : The dominant-baseline is shifted to the default position for subscripts.
- `super`
  - : The dominant-baseline is shifted to the default position for superscripts.
- `<length-percentage>`
  - : A length value raises (positive value) or lowers (negative value) the dominant-baseline of the parent text content element by the specified length.

    A percentage value raises (positive value) or lowers (negative value) the dominant-baseline of the parent text content element by the specified percentage of the {{SVGAttr("line-height")}}.

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}
