---
title: First Post
date: 2025-02-23 13:12:00 +0900
categories: [test, others]
tags: [test, demo]

author: bachng

description: This is a test.

toc: true

comments: true

image: 
    path: assets/img/post-0/5.jpg
    alt: mr-robot

pin: true

math: true

mermaid: true

---



## Image

![mr-robot](assets/img/post-0/8.jpg){: width="700" height="400" .normal .light .shadow}
_Bonjour, Elliot._


## Video
{% include embed/youtube.html id='YNGumKrXrlQ' %}

## Prompts
> Example line for prompt.
{: .prompt-info }


## Syntax

### inline code
`this is inline code`

### code lang
```cpp
int main(){
    std::vector<cv2::KeyPoint> keypoints;
    return 0;
}
```
{: file="assets/files/post-0/test.cpp"}


### filepath highlight

`assets/img/post-0/5.jpg`{: .filepath}


## Math

block math:

$$
scale_i = \frac{d_{true_i}}{d_{est_i}}
$$

block math, numbered:

$$
\begin{equation}
  \sum_{n=1}^\infty 1/n^2 = \frac{\pi^2}{6}
  \label{eq:series}
\end{equation}
$$

We can reference the equation as \eqref{eq:series}.

inline math: $$ CP^2 + t_z^2 - 2 CP t_z \cos(\pi/2 - \phi_c) = 0$$

inline math in lists:

1. \$$ 1+1=2 $$
2. \$$ 2+2=4 $$
3. \$$ 3+3=6 $$


## Diagrams with Mermaid

```mermaid
flowchart LR

    A[Hard] -->|act_1| B(Round)
    B -->|act_2| C{Decision}
    C -->|act_3_1| D[Result 1]
    C -->|act_3_2| E[Result 2]

```



<script src="https://cdn.jsdelivr.net/npm/mermaid@10.9.1/dist/mermaid.min.js"></script>

<script>
    mermaid.initialize({
        theme: 'neutral'
    });
</script>