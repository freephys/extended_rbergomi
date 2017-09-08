# Extended rBergomi

An extension of the rough Bergomi model which decouples smile and skew explosion rates, essentially by driving volatility dynamics by two (Volterra) processes of differing roughness. (The price process still only depends upon two Brownian motions in total.)

We are researching this model's theoretical justification (in the realised measure) and practical applications (in both realised and pricing measures), primarily in the context of the foreign exchange market (where we find standard rBergomi struggles to capture implied volatility observations). The model has thus far proved quite promising, in particular being able to generate steep symetric short-time smiles and skewed long-time smiles (an phenomenon which standard rBergomi cannot reproduce).

Python code and results forthcoming.
