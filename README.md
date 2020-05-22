# arXiv.org non-official badge implementation for Markdown files

This is unofficial badges implementation based on [shields.io](https://shields.io/) and [arxiv.org](https://arxiv.org/).

This project was inspired by the [badges](https://github.com/Naereen/badges) by [Lilian Besson](https://github.com/Naereen).

## Variations

Basic structure of badge looks like:

[![arXiv](https://img.shields.io/badge/arXiv-<INDEX>-<COLOR>.svg)](https://arxiv.org/abs/<INDEX>)

```markdown
[![arXiv](https://img.shields.io/badge/arXiv-<INDEX>-<COLOR>.svg)](https://arxiv.org/abs/<INDEX>)
```

where `INDEX` is part of URL address for paper which contains version of paper like `1234.56789v1`.

### Based on [arxiv.org](https://arxiv.org/) colors

> In this examples non-existent paper with id `1234.56789` was used.

---

Based on site footer colors:

[![arXiv](https://img.shields.io/badge/arXiv-1234.56789-b31b1b.svg)](https://arxiv.org/abs/1234.56789)

```markdown
[![arXiv](https://img.shields.io/badge/arXiv-1234.56789-b31b1b.svg)](https://arxiv.org/abs/1234.56789)
```

---

Based on site icon colors:

[![arXiv](https://img.shields.io/badge/arXiv-1234.56789-00ff00.svg)](https://arxiv.org/abs/1234.56789)

```markdown
[![arXiv](https://img.shields.io/badge/arXiv-1234.56789-00ff00.svg)](https://arxiv.org/abs/1234.56789)
```

---

Based on site icon colors:

[![arXiv](https://img.shields.io/badge/arXiv-1234.56789-f9f107.svg)](https://arxiv.org/abs/1234.56789)

```markdown
[![arXiv](https://img.shields.io/badge/arXiv-1234.56789-f9f107.svg)](https://arxiv.org/abs/1234.56789)
```

## Badge style

You can customize badges style adding `?style=` options. See more about styles in [https://shields.io/](https://shields.io/).

Examples:

[![arXiv](https://img.shields.io/badge/arXiv-1234.56789-b31b1b.svg?style=plastic)](https://arxiv.org/abs/1234.56789)

```markdown
[![arXiv](https://img.shields.io/badge/arXiv-1234.56789-b31b1b.svg?style=plastic)](https://arxiv.org/abs/1234.56789)
```

---

[![arXiv](https://img.shields.io/badge/arXiv-1234.56789-b31b1b.svg?style=flat)](https://arxiv.org/abs/1234.56789)

```markdown
[![arXiv](https://img.shields.io/badge/arXiv-1234.56789-b31b1b.svg?style=flat)](https://arxiv.org/abs/1234.56789)
```

---

[![arXiv](https://img.shields.io/badge/arXiv-1234.56789-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/1234.56789)

```markdown
[![arXiv](https://img.shields.io/badge/arXiv-1234.56789-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/1234.56789)
```

---

[![arXiv](https://img.shields.io/badge/arXiv-1234.56789-b31b1b.svg?style=for-the-badge)](https://arxiv.org/abs/1234.56789)

```markdown
[![arXiv](https://img.shields.io/badge/arXiv-1234.56789-b31b1b.svg?style=for-the-badge)](https://arxiv.org/abs/1234.56789)
```

## References

* This project was inspired by the [badges](https://github.com/Naereen/badges) by [Lilian Besson](https://github.com/Naereen);
* [shields.io](https://shields.io/) service used for this badges;
* [arxiv.org](https://arxiv.org/) name and colors used for this badges.

## License

[![License: Unlicense](https://img.shields.io/badge/License-Unlicense-green.svg)](https://unlicense.org/)

This project is licensed under the terms of the [Unlicense](https://unlicense.org/) (see [LICENSE](<https://github.com/zsxoff/arxiv-badge/blob/master/LICENSE>) file).
