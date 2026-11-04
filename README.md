<!-- HERO:START -->
<p align="center">
  <a href="https://github.com/juw12/Explicit-Maccormack-Method"><img src="docs/media/banner.jpg" alt="Explicit MacCormack Method: The explicit MacCormack scheme for 1-D wave propagation." width="100%"></a>
</p>

<p align="center">
  <b>The explicit MacCormack scheme for 1-D wave propagation.</b><br>
  A computational fluid dynamics study of a predictor-corrector scheme, with plotted results.
</p>

<p align="center">
  <a href="#see-it-in-action">See it in action</a> ·
  <a href="#highlights">Highlights</a> ·
  <a href="https://github.com/juw12">More by juw12</a>
</p>

<p align="center">
  <a href="https://github.com/juw12/Explicit-Maccormack-Method"><img src="https://img.shields.io/github/last-commit/juw12/Explicit-Maccormack-Method?label=updated&color=0891b2" alt="Last updated"></a>
  <img src="https://img.shields.io/badge/CFD-24292f" alt="CFD">
  <img src="https://img.shields.io/badge/Gnuplot-24292f" alt="Gnuplot">
</p>

<a id="highlights"></a>
<table>
  <tr>
    <td width="33%" valign="top">
      <b>Predictor-corrector</b><br>
      A second-order explicit scheme for the 1-D wave equation.
    </td>
    <td width="33%" valign="top">
      <b>Plotted results</b><br>
      Solutions at several time levels, plotted with Gnuplot.
    </td>
    <td width="33%" valign="top">
      <b>Compare schemes</b><br>
      Pairs with the Upwind Differencing study.
    </td>
  </tr>
</table>

## See it in action

<p align="center">
  <a href="https://github.com/juw12/Explicit-Maccormack-Method"><img src="maccormack_1_5_10.png" alt="Explicit MacCormack Method screenshot" width="820"></a><br>
  <sub>Explicit MacCormack Method in use</sub>
</p>
<!-- HERO:END -->

## About

The one dimensional wave propagation equation is given by 

<img width="219" alt="image" src="https://user-images.githubusercontent.com/73946469/126501812-364fb701-13a0-4ab8-8dda-539beab539f8.png">

<img width="220" alt="image" src="https://user-images.githubusercontent.com/73946469/126501825-11d2c7d8-2b01-4ef6-9911-5c7e782409b2.png">

where the initial conditions are to be stated by
<img width="364" alt="image" src="https://user-images.githubusercontent.com/73946469/126501764-b9d3242a-3e84-448f-8e05-e37ef561b794.png">
<img width="416" alt="image" src="https://user-images.githubusercontent.com/73946469/126501779-23f87ac2-0ac1-4707-821e-b18cd34eab37.png">

Dx is fixed to a value of 0.01, while u’s and dt’s values are given by 0.09 and 0.01

The solution by the explicit two step predictor-corrector Maccormack method is to be given by the equations below.

<img width="267" alt="image" src="https://user-images.githubusercontent.com/73946469/126502164-dbfe98ee-7481-49cd-bae8-e71515e01506.png">
<img width="387" alt="image" src="https://user-images.githubusercontent.com/73946469/126502199-e5767d6d-8caf-4d69-8ca7-95b3ea94cbda.png">

where the scheme is nonlinear for C ≤1, having an order of accuracy of [(∆𝑡)^2,(∆𝑥)^2].

## License

Released under the [MIT License](LICENSE) © 2026 Juwen Lie. Contributions are welcome under the same license; see the [contributing guide](https://github.com/juw12/.github/blob/main/CONTRIBUTING.md) and [Code of Conduct](https://github.com/juw12/.github/blob/main/CODE_OF_CONDUCT.md).
