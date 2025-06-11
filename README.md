# ros2_stage_robot-controller
Controlador do robô navegador
Sobre o projeto:
Controle do robô diferencial no ambiente de simulação Stage, para alcançar as coordenada dos alvos desejados.

Pré-requisitos:
Ubuntu 22.04
ROS 2
Stage

Com o terminal do ubuntu aberto, execute o seguinte comando:
cd ros2_ws/

Em seguida execute o script para abrir o ambiente Stage:

ros2 launch my_py_pkg my_robot_simulation_launch.py

Após o simulador aberto, execute o script em python:

ros2 run my_py_pkg robot_controller_node.py

Ai o robô ira iniciar a navegação pelas coordenadas (x= -7 , y= -7), em direção aos alvos 1-( x=7,y=7) e 2(x=7,y=-3).

[Vídeo explicativo:]https://youtu.be/c1-k95NCYjE?si=eLN1wx4Hge_uh7GH
