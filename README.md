Use this format for graph questions.

Important rule:
Each step may show the axes for orientation, but it must show ONLY the new item being added besides the axes.

Allowed in every step:
- axes
- the new curve, line, point, label, or shading instruction

Do NOT redraw:
- previous curves
- previous labels
- previous points
- previous shading

Use LaTeX array format only:

$$
\begin{array}{l}
...
\end{array}
$$

Use \quad for spacing.
Do not use normal spaces for graph positioning.
Do not use TikZ.
Do not use PGFPlots.
Do not use ASCII art outside LaTeX.

==================================================
EXAMPLE: POSITIVE EXTERNALITY
==================================================

GRAPH: POSITIVE EXTERNALITY

Goal:
Show that the market underproduces because social marginal benefit is greater than private marginal benefit.

Step 1: Draw axes

Description:
Draw Price / Cost / Benefit on the vertical axis and Quantity on the horizontal axis.

LaTeX guide:
$$
\begin{array}{l}
\mathrm{P/B/C}\\
|\\
|\\
|\\
|\\
+--------\mathrm{Q}
\end{array}
$$

Step 2: Add Supply

Description:
Draw a straight upward-sloping line. Start near the lower-left and move toward the upper-right. Label it S.

LaTeX guide:
$$
\begin{array}{l}
\mathrm{P/B/C}\\
|\quad\quad\quad/ \mathrm{S}\\
|\quad\quad/\\
|\quad/\\
|/\\
+--------\mathrm{Q}
\end{array}
$$

Step 3: Add PMB

Description:
Draw a straight downward-sloping line. Start near the upper-left and move toward the lower-right. Label it PMB. Do not include Supply in this LaTeX guide.

LaTeX guide:
$$
\begin{array}{l}
\mathrm{P/B/C}\\
|\quad\backslash \mathrm{PMB}\\
|\quad\quad\backslash\\
|\quad\quad\quad\backslash\\
|\quad\quad\quad\quad\backslash\\
+--------\mathrm{Q}
\end{array}
$$

Step 4: Add MSB

Description:
Draw another straight downward-sloping line above where PMB would be. Keep it roughly parallel to PMB. Label it MSB. Do not include PMB or Supply in this LaTeX guide.

LaTeX guide:
$$
\begin{array}{l}
\mathrm{P/B/C}\\
|\quad\backslash \mathrm{MSB}\\
|\quad\quad\backslash\\
|\quad\quad\quad\backslash\\
+--------\mathrm{Q}
\end{array}
$$

Step 5: Add Market point

Description:
On your hand-drawn graph, mark the Market point where PMB intersects Supply. This should be the left equilibrium point. Label it Mkt.

LaTeX guide:
$$
\begin{array}{l}
\mathrm{P/B/C}\\
|\\
|\quad\times \mathrm{Mkt}\\
|\\
|\\
+--------\mathrm{Q}
\end{array}
$$

Step 6: Add Efficient point

Description:
On your hand-drawn graph, mark the Efficient point where MSB intersects Supply. This should be to the right of the Market point. Label it Eff.

LaTeX guide:
$$
\begin{array}{l}
\mathrm{P/B/C}\\
|\\
|\quad\quad\quad\times \mathrm{Eff}\\
|\\
|\\
+--------\mathrm{Q}
\end{array}
$$

Step 7: Add quantity labels

Description:
Drop a vertical dashed line from Market to the Quantity axis and label it Qm. Drop another vertical dashed line from Efficient to the Quantity axis and label it Q*. Qm must be left of Q*.

LaTeX guide:
$$
\begin{array}{l}
\mathrm{P/B/C}\\
|\\
|\\
|\\
|\\
+--------\mathrm{Q}\\
\quad Q_m\quad Q^*
\end{array}
$$

Step 8: Shade DWL

Description:
Shade the triangle between Qm and Q*. It is right of Qm, left of Q*, below MSB, and above Supply. Label it DWL.

LaTeX guide:
$$
\begin{array}{l}
\mathrm{P/B/C}\\
|\\
|\quad\quad\mathrm{DWL}\\
|\\
|\\
+--------\mathrm{Q}
\end{array}
$$

Final check:
$$
\begin{array}{l}
MSB>PMB\\
Q_m<Q^*\\
Underproduction\\
DWL\ exists
\end{array}
$$

Explanation:
Because there is a positive externality, social marginal benefit is greater than private marginal benefit, so MSB is drawn above PMB. The market equilibrium occurs where PMB meets Supply, giving Qm. The socially efficient equilibrium occurs where MSB meets Supply, giving Q*. Since Qm is less than Q*, the good is underproduced. The deadweight loss is the triangle between Qm and Q*, below MSB and above Supply.
