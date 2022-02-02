<p align="center">
  <img src="/HCSS%20Logo.svg" width="50%">
</p>
<p align="center">HCSS (Hydra CSS) is a modified (and hopefully improved) version of CSS that provides extra functionality and syntax shortcuts. It is not like most other CSS preprocessors. HCSS does not allow blatantly invalid syntax, and is not as forgiving in many aspects. This allows HCSS to stay readable and consistent across projects.</p>

# Notes
- Invalid syntax is NOT allowed. Normally CSS parsers just skip invalid syntax, but I don't think there is really a reason to use invalid syntax in HCSS. The HCSS parser will error and notify you if there is invalid syntax.
- Nesting requires the nesting selector `&` before each selector. This enhances readability and allows people to quickly spot where extra rules are.
- Unlike other similar projects, variables and custom media queries must be defined before they are used. This keeps the code organized and accessible to other developers.
