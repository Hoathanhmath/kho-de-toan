<script type="text/tikz">
  \begin{tikzpicture}[scale=0.9]
    % Vẽ trục tọa độ
    \draw[->, thick] (-1,0) -- (4.5,0) node[below] {$x$};
    \draw[->, thick] (0,-3.5) -- (0,3.5) node[left] {$y$};
    \node[below left] at (0,0) {$O$};
    
    % Vẽ đồ thị hàm số y = x^3 - 6x^2 + 9x - 2
    \draw[thick, domain=-0.3:3.8, samples=100] plot (\x, {\x*\x*\x - 6*\x*\x + 9*\x - 2});
    
    % Vẽ nét đứt cực trị và điền tọa độ
    \draw[dashed] (1,0) node[below] {$1$} -- (1,2) -- (0,2) node[left] {$2$};
    \draw[dashed] (3,0) node[above right] {$3$} -- (3,-2) -- (0,-2) node[left] {$-2$};
  \end{tikzpicture}
</script>