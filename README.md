# f110-rrt
rrt path planning in f1tenth simulator
![Screenshot from 2022-05-20 15-21-36](https://user-images.githubusercontent.com/75038294/169503347-d01f25a2-ad5e-4786-a520-17c3b02419c6.png)

#installing xtensor
1. conda install -c conda-forge xtensor

#installing xtensor interpolate
1. git clone git@github.com:rjsberry/xtensor-interpolate.git
2. cd xtensor-interpolate
3. mkdir build && cd build
4. sudo apt install gfortran
5. cmake -G "Unix Makefiles" ..
6. cmake --build .
7. sudo make install
