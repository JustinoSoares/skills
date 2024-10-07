## philosophers

A ideia desse projecto é solucionar o problema da alimentação dos philosophores, que tem as seguintes regras.
- Deve receber 5 ou 6 parametros `number_of_philosopher` `time_to_die` `time_to_eat` ` time_to_sleep` `number_of_times_each_philosopher_must_eat (optional argument)`
- O número de philosophes não pode exceder `200`
- O tempo de morrer, tempo de comer e tempo de dormir não podem ser menores que `60` milisegundos

# Time
Estrutura para o tempo 
```c
struct timeval time;
struct timezone zone;
```

Obter o tempo actual
```c
gettimeofday(&time_da_estrutura_timeval, &time_da_estrutura_timezone);
```
