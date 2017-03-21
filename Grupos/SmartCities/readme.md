### 4) Smart Cities - Desafio IoT ok

A prefeitura de São Paulo está com um projeto de smart cities com foco em 2 problemas: 1) mapear a poluição sonora produzido pelo trânsito e 2) informar a população o nível de temperatura e umidade das regiões da cidade para alertar quanto as pancadas de chuvas isoladas que causam transtornos para a população. Além do app que deverá ser disponibilizado para a população, deverá ser oferecido para a defesa civil um dashboard para que os gestores sejam capazes de tomar decisões e análises quanto aos principais pontos de risco da cidade (quanto a chuva).

Para fins de análise, o ruído será calculado com a seguinte fórmula: 
double db = 16.801 * log (sensorValue/1023) + 9.872;