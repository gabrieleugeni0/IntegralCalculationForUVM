# Uniformly Varied Movement - Euler Integration

Calculate position (y) of an object that was thrown up, according to time (t).

Two methods are used:

- Euler Method

$$y_{i+1} = y_i + h \frac{dy(t)}{dt}$$

- Analytical solution

$$v(t) = v_0 - gt = \frac{dy}{dt} = v_0 - gt \to y = \int_0^{t} v_0 - gt dt \to y(t) = y_0 + v_0 t - \frac{gt^2}{2}$$

###### Install requirements:

```
$ pip install numpy
```

```
$ pip install matplotlib
```

##### - Create a function using Numerical Calculation by Euler Method and Analytical solution, calculate position (y) in function of the time (t) and plot the informations in a graphic
##### - Code are commented with steps

###### To run the script: It's just run the code cells of the notebook