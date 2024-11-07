<h1 align="center">MedTest</h1>

## Player

Script do player (Medico)
```C#
public void setCanMove(bool can){}//define se o player pode ou nao mover
private void Move(){}//faz a movimentação e animação do player
```

## Botoes

Script dos botoes
```C#
public void Jogar(){}//carrega a cena do jogo
public void Sair(){}//fecha o aplicativo
public void Sobre(){}//Carrega a cena sobre o Jogo
```

## Velho

Script do paciente
```C#
//Todos os moves do paciente congela os moves do Player
private void Move1(){}//Movimento 1 do paciente: move da porta pra cadeira - acontece por automatico no inicio do jogo
private void Move2(){}//Movimento 2 do paciente: move da cadeira para a maca
private void Move3(){}//Movimento 3 do paciente: move da maca para a cadeira
private void Move4(){}//Movimento 4 do paciente: move da cadeira para fora do mapa

public void setCanMove1(bool can){} //libera o Move2 para ocorrer
public void setCanMove2(bool can){} //libera o Move3 para ocorrer
public void setCanMove3(bool can){} //libera o Move4 para ocorrer
```