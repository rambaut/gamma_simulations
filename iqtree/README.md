## IQTree files

Results from running `IQTree2` on the simulated data under different models - Discrete Gamma (e.g., G4, G16 etc) or Free Rates (e.g., R4, R16 etc).

Data simulated using continuous gamma with alpha = 0.1, 1.0 or 10.0 (`a0.1`, etc in the file name). Files with `CP` were simulated with a 3 rate codon position model.

### Summary of results

Simulated: 
no rate heterogeneity

Reconstructed: 
Model of substitution: HKY+F
tree length: 21.9781

-----

Simulated: 
alpha = 0.1

Reconstructed: 
Model of substitution: HKY+F+G4
Gamma shape alpha: 0.2225
Log-likelihood of the tree: -219377.4312 (s.e. 2972.8211)
Corrected Akaike information criterion (AICc) score: 439010.1040
Total tree length (sum of branch lengths): 28.9309

Model of substitution: HKY+F+G6
Gamma shape alpha: 0.1648
Log-likelihood of the tree: -217157.8309 (s.e. 2973.5903)
Corrected Akaike information criterion (AICc) score: 434570.9033
Total tree length (sum of branch lengths): 28.0922

Model of substitution: HKY+F+G8
Gamma shape alpha: 0.1415
Log-likelihood of the tree: -216374.1753 (s.e. 2974.5038)
Corrected Akaike information criterion (AICc) score: 433003.5922
Total tree length (sum of branch lengths): 26.9231

Model of substitution: HKY+F+G16
Gamma shape alpha: 0.1016
Log-likelihood of the tree: -215685.4202 (s.e. 2985.0435)
Corrected Akaike information criterion (AICc) score: 431626.0820 <<----- best
Total tree length (sum of branch lengths): 23.1125

Model of substitution: HKY+F+R4
Site proportion and rates:  (0.6474,0.007297) (0.14,0.3489) (0.1029,1.633) (0.1097,7.097)
Log-likelihood of the tree: -216496.5236 (s.e. 2997.3223)
Corrected Akaike information criterion (AICc) score: 433258.5519
Total tree length (sum of branch lengths): 15.6671

Model of substitution: HKY+F+R16
Site proportion and rates:  (0.4359,0.003365) (0.1796,0.00344) (0.01741,0.1123) (0.05084,0.1254) (0.03687,0.1256) (0.02213,0.2903) (0.02099,0.3869) (0.01808,0.5348) (0.01769,0.6299) (0.01461,0.7401) (0.01443,1.05) (0.01959,1.223) (0.01826,1.417) (0.03866,2.264) (0.04755,4.319) (0.04746,12.24)
Log-likelihood of the tree: -215662.1259 (s.e. 2986.8538)
Corrected Akaike information criterion (AICc) score: 431639.1643
Total tree length (sum of branch lengths): 21.1244 <<----- closest

-----

Simulated: 
alpha = 1.0

Reconstructed: 
Model of substitution: HKY+F+G4
Gamma shape alpha: 0.8941
Log-likelihood of the tree: -478802.0991 (s.e. 2318.5381)
Corrected Akaike information criterion (AICc) score: 957859.4397
Total tree length (sum of branch lengths): 21.8892

Model of substitution: HKY+F+G16
Gamma shape alpha: 0.9931
Log-likelihood of the tree: -478230.4161 (s.e. 2316.2698)
Corrected Akaike information criterion (AICc) score: 956716.0738 <<----- best
Total tree length (sum of branch lengths): 22.0113 <<----- closest

Model of substitution: HKY+F+R4
Site proportion and rates:  (0.2041,0.09733) (0.314,0.463) (0.304,1.158) (0.1779,2.713)
Log-likelihood of the tree: -478614.1068 (s.e. 2316.2748)
Corrected Akaike information criterion (AICc) score: 957493.7182
Total tree length (sum of branch lengths): 21.2699

-----

Simulated: 
alpha = 10.0

Reconstructed: 
Model of substitution: HKY+F+G4
Gamma shape alpha: 9.079
Log-likelihood of the tree: -569712.1512 (s.e. 1065.6511)
Corrected Akaike information criterion (AICc) score: 1139679.5440
Total tree length (sum of branch lengths): 21.9535 <<----- closest

Model of substitution: HKY+F+G16
Gamma shape alpha: 10.01
Log-likelihood of the tree: -569682.9036 (s.e. 1065.5265)
Corrected Akaike information criterion (AICc) score: 1139621.0488 <<----- best
Total tree length (sum of branch lengths): 21.9881

Model of substitution: HKY+F+R4
Site proportion and rates:  (0.004912,0.2867) (0.2853,0.6272) (0.5727,1.038) (0.1371,1.644)
Log-likelihood of the tree: -569679.9150 (s.e. 1065.5818)
Corrected Akaike information criterion (AICc) score: 1139625.3346
Total tree length (sum of branch lengths): 21.9992

-----

Simulated: 
cp = 0.5 0.25 2.25

Reconstructed: 
Model of substitution: HKY+F+R4
Site proportion and rates:  (0.2931,0.2388) (0.2766,0.4489) (0.0977,0.5812) (0.3326,2.252)
Log-likelihood of the tree: -479560.6084 (s.e. 2178.5023)
Corrected Akaike information criterion (AICc) score: 959386.7218
Total tree length (sum of branch lengths): 22.0091

Model of substitution: HKY+F+R3
Site proportion and rates:  (0.3337,0.2494) (0.3332,0.5026) (0.3331,2.249)
 Category  Relative_rate  Proportion
  1         0.2494         0.3337
  2         0.5026         0.3332
  3         2.249          0.3331
Log-likelihood of the tree: -479560.9728 (s.e. 2178.4836)
Corrected Akaike information criterion (AICc) score: 959383.3441 <<----- best
Total tree length (sum of branch lengths): 21.9852 <<----- closest

Model of substitution: HKY+F+G4
Gamma shape alpha: 1.295
 Category  Relative_rate  Proportion
  1         0.1918         0.25
  2         0.5504         0.25
  3         1.036          0.25
  4         2.222          0.25
Log-likelihood of the tree: -481553.2752 (s.e. 2171.2538)
Corrected Akaike information criterion (AICc) score: 963361.7923
Total tree length (sum of branch lengths): 21.5329

Model of substitution: HKY+F+G3
Gamma shape alpha: 1.237
 Category  Relative_rate  Proportion
  1         0.2385         0.3333
  2         0.7629         0.3333
  3         1.999          0.3333
Log-likelihood of the tree: -481297.4737 (s.e. 2165.7724)
Corrected Akaike information criterion (AICc) score: 962850.1893
Total tree length (sum of branch lengths): 22.5066


