# Optimization

Use the following commands to install GLPK:
```
sudo apt update
sudo apt install glpk-utils
glpsol --version
```

Command to create and activate virutal environment: 

```
virtualenv myenv
source myenv/bin/activate
```

This is a way to install ipopt solver for non linear problems with pyomo

```
!wget -N -q "https://matematica.unipv.it/gualandi/solvers/ipopt-linux64.zip"
!unzip -o -q ipopt-linux64
```

## Linearization techniques

### Big M:
Binary * Continous

```
C = b*x
Where b is binary, x is continuos
=====>
-b*M <= C >= b*M
-(1-b)*M <= C-x >= (1-b)*M
```

## Other sources

Vehicle Routing problems
https://developers.google.com/optimization/routing/vrp?hl=es-419