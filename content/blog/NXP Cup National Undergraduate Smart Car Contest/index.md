---
title: NXP Cup Undergraduate Smart Car Contest
summary: Intelligent Chess Gaming Robot.
date: 2019-08-24
math: true
authors:
  - admin
tags:
  - Bachelor
  - Robotics

image:
  caption: 'NXP Cup Logo'

---

## Abstract

The control platform is capable of movement at speeds of up to 2.5 m/s. Image preprocessing utilises inverse perspective transformation and adaptive binarization, while template matching is employed for recognition purposes. The combination of images with the air posture speculation algorithm enables accurate location of the The position of the platform is aligned with the established map through the utilisation of probabilistic statistical methods to identify the relevant components within the map. Intelligent algorithms are employed, based on the simulated annealing algorithm and the adaptive cooling table, for the omnidirectional gaming platform, with the objective of planning the shortest moving path.

## Video

Teach your course by sharing videos with your students. Choose from one of the following approaches:

**Youtube**:

    {{</* youtube D2vj0WcvH5c */>}}

{{< youtube xtMpb3qdb-k>}}

**Bilibili**:

    {{</* bilibili BV1WV4y1r7DF */>}}

{{< bilibili BV1WV4y1r7DF >}}

**Video file**

Videos may be added to a page by either placing them in your `assets/media/` media library or in your [page's folder](https://gohugo.io/content-management/page-bundles/), and then embedding them with the _video_ shortcode:

    {{</* video src="my_video.mp4" controls="yes" */>}}

## Podcast

You can add a podcast or music to a page by placing the MP3 file in the page's folder or the media library folder and then embedding the audio on your page with the _audio_ shortcode:

    {{</* audio src="ambient-piano.mp3" */>}}

Try it out:

{{< audio src="ambient-piano.mp3" >}}

## Test students

Provide a simple yet fun self-assessment by revealing the solutions to challenges with the `spoiler` shortcode:

```markdown
{{</* spoiler text="👉 Click to view the solution" */>}}
You found me!
{{</* /spoiler */>}}
```

renders as

{{< spoiler text="👉 Click to view the solution" >}} You found me 🎉 {{< /spoiler >}}

## Math

Hugo Blox Builder supports a Markdown extension for $\LaTeX$ math. Enable math by setting the `math: true` option in your page's front matter, or enable math for your entire site by toggling math in your `config/_default/params.yaml` file:

```yaml
features:
  math:
    enable: true
```

To render _inline_ or _block_ math, wrap your LaTeX math with `$...$` or `$$...$$`, respectively.

Example **math block**:

```latex
$$
\gamma_{n} = \frac{ \left | \left (\mathbf x_{n} - \mathbf x_{n-1} \right )^T \left [\nabla F (\mathbf x_{n}) - \nabla F (\mathbf x_{n-1}) \right ] \right |}{\left \|\nabla F(\mathbf{x}_{n}) - \nabla F(\mathbf{x}_{n-1}) \right \|^2}
$$
```

renders as

$$\gamma_{n} = \frac{ \left | \left (\mathbf x_{n} - \mathbf x_{n-1} \right )^T \left [\nabla F (\mathbf x_{n}) - \nabla F (\mathbf x_{n-1}) \right ] \right |}{\left \|\nabla F(\mathbf{x}_{n}) - \nabla F(\mathbf{x}_{n-1}) \right \|^2}$$

Example **inline math** `$\nabla F(\mathbf{x}_{n})$` renders as $\nabla F(\mathbf{x}_{n})$.

Example **multi-line math** using the math linebreak (`\\`):

```latex
$$f(k;p_{0}^{*}) = \begin{cases}p_{0}^{*} & \text{if }k=1, \\
1-p_{0}^{*} & \text{if }k=0.\end{cases}$$
```

renders as

$$
f(k;p_{0}^{*}) = \begin{cases}p_{0}^{*} & \text{if }k=1, \\
1-p_{0}^{*} & \text{if }k=0.\end{cases}
$$

## Code

Hugo Blox Builder utilises Hugo's Markdown extension for highlighting code syntax. The code theme can be selected in the `config/_default/params.yaml` file.


    ```python
    import pandas as pd
    data = pd.read_csv("data.csv")
    data.head()
    ```

renders as

```python
import pandas as pd
data = pd.read_csv("data.csv")
data.head()
```

## Inline Images

```go
{{</* icon name="python" */>}} Python
```

renders as

{{< icon name="python" >}} Python

## Did you find this page helpful? Consider sharing it 🙌
