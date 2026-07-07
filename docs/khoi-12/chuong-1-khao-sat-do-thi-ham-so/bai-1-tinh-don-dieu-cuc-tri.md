### Dạng thức 1. Câu trắc nghiệm nhiều phương án lựa chọn

**Câu 1.** Cho hàm số $y=f(x)$ liên tục trên $\mathbb{R}$ và có đồ thị như hình vẽ bên dưới:

<script type="text/tikz">
  \usepackage{pgfplots}
  \pgfplotsset{compat=1.18}
  \begin{document}
    \begin{tikzpicture}
    \begin{axis}[
        width=6.5cm, height=6.5cm,
        axis lines=middle, 
        grid=none,
        xmin=-1.5, xmax=4.5, ymin=-3.5, ymax=3.5,
        xtick={1,3}, ytick={-2,2},
        xlabel=$x$, ylabel=$y$,
        every axis x label/.style={at={(current axis.right of origin)},anchor=north},
        every axis y label/.style={at={(current axis.above origin)},anchor=east},
        samples=300, smooth] 
        
        \addplot[thick, domain=-0.5:4] {x^3 - 6*x^2 + 9*x - 2};
        \draw[dashed, thin] (1,0) -- (1,2) -- (0,2);
        \draw[dashed, thin] (3,0) -- (3,-2) -- (0,-2);
        \node[below left] at (0,0) {$O$};
    \end{axis}
    \end{tikzpicture}
  \end{document}
</script>

Điểm cực đại của hàm số đã cho là:
- A. $x=1$.
- B. $x=3$.
- C. $x=2$.
- D. $x=-2$.

??? success "Xem lời giải chi tiết"
    **Đáp án đúng: A**

    Quan sát đồ thị, ta thấy điểm nhô lên cao nhất trong một vùng lân cận (điểm cực đại) tương ứng với hoành độ $x=1$ và tung độ $y=2$. Vậy điểm cực đại của hàm số là $x=1$.