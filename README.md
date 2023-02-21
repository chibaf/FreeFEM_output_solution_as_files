# FreeFEM_output_solution_as_files
FreeFEM_output_solution_as_files


solution:

<img width="612" alt="Screen Shot 2023-02-21 at 23 45 31" src="https://user-images.githubusercontent.com/1296728/220376642-d1a605f8-360a-4d53-8f13-193a754c3d38.png">

gnuplot> set palette rgbformulae 30,31,32

gnuplot> splot "s.txt" w l pal

gnuplot> set term png

Terminal type set to 'png'

Options are 'nocrop medium '

gnuplot> set output "u.png"

gnuplot> replot

smooth palette in png: available 157 color positions; using 157 of them

![u](https://user-images.githubusercontent.com/1296728/220378808-6c73ee64-2741-4aa2-afe3-2d835ac5fe66.png)

