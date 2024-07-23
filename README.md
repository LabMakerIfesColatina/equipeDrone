# equipeDrone

---

# Drone para Flying Robot Trial League - RoboCup Brasil

Bem-vindo ao repositório do Drone para a competição Flying Robot Trial League da RoboCup Brasil. Este repositório contém o código-fonte, a documentação e os recursos necessários para desenvolver e operar um drone que atenda aos pré-requisitos estipulados pela competição.

## Pré-requisitos do Drone

Os Drones que participarão das fases da competição devem atender aos seguintes pré-requisitos, que serão verificados durante a fase de inspeção:

1. **Localização:**
   - O Drone não poderá utilizar sistemas GPS ou RTK-GPS para localizar-se na arena.
   - Nenhum sistema de auxílio externo à arena (ex.: beacons) poderá ser utilizado na localização do Drone.

2. **Autonomia:**
   - Durante as fases do desafio, os Drones devem agir autonomamente, sem qualquer controle externo ou intervenção humana, exceto em situações de emergência que acarretarão na finalização da tentativa da fase que estiver sendo executada.

3. **Propulsão e Energia:**
   - Só serão permitidos Drones impulsionados por motores elétricos e de energia através de baterias incorporadas no robô.
   - É proibida a utilização de helicópteros, veículos com motores de combustão ou balões de gás.

4. **Segurança:**
   - Drones com peso acima de 100 gramas devem possuir um botão (kill switch) que arme ou desarme os motores e deve ser localizado no drone.
   - O uso de qualquer tipo de hardware de controle e detecção embutida no Drone é permitido, desde que não ofereçam risco para os participantes ou para o público devido à emissão de radiação ou outro nível de sinal considerado inseguro para os seres humanos.

5. **Desafios:**
   - Durante os desafios, é proibida a utilização de fios, cabos e/ou cordões umbilicais para controle, comunicação ou qualquer outro propósito.
   - O Drone deve ser capaz de manter uma posição fixa em relação ao solo a uma altura mínima de um (1) metro.

6. **Supervisão Remota:**
   - Embora o Drone deva atuar autonomamente durante os desafios, a equipe deve manter constantemente a supervisão remota do robô voador, de acordo com a legislação vigente, assegurando a retomada do controle do robô voador por quaisquer problemas técnicos e/ou instabilidade.

7. **Comunicação:**
   - O Drone poderá ter a sua malha de controle embarcada ou poderá receber comandos de controle de forma remota (i.e., através de um computador que envie os comandos).
   - No caso de controle remoto, a equipe deve ter um sistema de comunicação (rádio, wi-fi ou bluetooth) dedicado entre o computador remoto da equipe que irá processar as informações e o robô. A organização não se responsabilizará por interferências no sinal de comunicação.

8. **Peso e Dimensões:**
   - Os Drones podem ter um peso máximo de 10 quilogramas.
   - A distância máxima entre os eixos dos hélices deve ser de 500 mm.

## Estrutura do Repositório

- `src/`: Código-fonte do drone.
- `docs/`: Documentação do projeto.
- `hardware/`: Especificações e diagramas do hardware utilizado.
- `simulations/`: Arquivos de simulação para testes do drone.
- `tests/`: Scripts de testes automatizados.

## Como Contribuir

Contribuições são bem-vindas! Por favor, siga os passos abaixo para contribuir:

1. Fork este repositório.
2. Crie uma nova branch (`git checkout -b feature/nova-feature`).
3. Faça suas alterações e commit (`git commit -m 'Adiciona nova feature'`).
4. Envie para a branch (`git push origin feature/nova-feature`).
5. Abra um Pull Request.

## Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

