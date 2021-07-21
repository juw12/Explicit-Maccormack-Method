# Explicit-Maccormack-Method
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

