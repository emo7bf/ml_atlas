# ml_atlas

Short, looping animations for building **intuition** in algorithms and machine
learning. Each video teaches exactly one idea, and every number on screen is
computed live by the real algorithm it illustrates — nothing is faked.

This material is meant as **free learning content for anyone** looking for
conceptual grounding in computer science or ML — students, self-learners, and
interview preppers alike. **You are free to use, share, and distribute these
videos** for any purpose; attribution is appreciated but not required.

Formats: every animation is available as an `.mp4` (in [`videos/`](videos/))
and a looping `.gif` (in [`gifs/`](gifs/)).

## Algorithms & Data Structures

| Animation | The one idea |
|---|---|
| [hash_tables](videos/hash_tables.mp4) | O(1) is conditional — watch a hash be computed digit by digit, a collision chain grow, and the probe counter pay for it |
| [trees](videos/trees.mp4) | Height is the cost: the same 7 keys build a height-7 chain or a height-3 tree depending only on insertion order |
| [graph_search](videos/graph_search.mp4) | BFS vs DFS is one data-structure swap: queue vs stack, same graph, different visit order |
| [dynamic_programming](videos/dynamic_programming.mp4) | Memoization collapses fib(6)'s 25-call tree to 7 evaluations — follow the first repeated subproblem by hand |
| [complexity](videos/complexity.mp4) | Growth class decides what survives doubling: real op counts at n = 8 and 16, then the measured multipliers |

## Machine Learning

| Animation | The one idea |
|---|---|
| [bias_variance](videos/bias_variance.mp4) | Resampled fits reveal the decomposition: lines all miss alike (bias), degree-9 fits scatter (variance) |
| [regularization](videos/regularization.mp4) | L2 ball vs L1 diamond — sparsity comes from corners |
| [learning_curves](videos/learning_curves.mp4) | More data helps until the noise floor: train error rises to σ², test error falls to it |
| [gradient_descent](videos/gradient_descent.mp4) | Step size must respect curvature: crawl, converge, or diverge on the same bowl |
| [sgd_minibatch](videos/sgd_minibatch.mp4) | Batch size is a noise dial: measured wander shrinks like 1/√B |
| [calibration](videos/calibration.mp4) | Confident ≠ correct: a reliability diagram catches an overconfident model, ECE computed from the bins |
| [embeddings3d](videos/embeddings3d.mp4) | Neighbors in a 2-D projection can lie — the 3-D view tells the truth |
| [attention](videos/attention.mp4) | Attention is a differentiable soft dictionary: softmax of real dot products decides where "it" looks |
| [double_descent](videos/double_descent.mp4) | Past the interpolation point, test error falls *again* |
| [scaling_laws](videos/scaling_laws.mp4) | On log-log axes a power law is a straight line — fit small runs, predict the big one |

## Previews

![graph_search](gifs/graph_search.gif)

![learning_curves](gifs/learning_curves.gif)

![dynamic_programming](gifs/dynamic_programming.gif)

---

Built with [Manim Community](https://www.manim.community/). Rendered in the
"candlelit" style: warm parchment, Garamond, semantically colored equations.
