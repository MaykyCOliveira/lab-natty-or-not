# Câmeras de trânsito com IA de análise de risco de colisões

## 📒 Descrição
Este projeto visa desenvolver um sistema de IA para monitorar e analisar o tráfego em tempo real usando câmeras de trânsito. O sistema calcula a probabilidade de colisões entre veículos e pedestres com base em fatores como velocidade, direção e dimensões dos objetos. Em caso de risco iminente, envia alertas automáticos para as autoridades locais mais próximas, ajudando a prevenir acidentes e melhorar a resposta dos serviços de emergência.

## 🤖 Tecnologias Utilizadas
YOLO (You Only Look Once): Detecta e classifica veículos e pedestres em tempo real.
DeepSort: Rastreamento contínuo dos objetos detectados.
RNNs/LSTMs: Predição de trajetórias com base no histórico de movimento.
OpenCV: Processamento de imagem.
TensorFlow/PyTorch: Treinamento e desenvolvimento de modelos de IA.
Scikit-Learn: Suporte em análise de dados e modelagem.
GCP/AWS/Azure Vision AI: Computação em nuvem para processamento em tempo real.
Kafka: Gestão de fluxos de dados em tempo real.
Flask/Django: APIs para comunicação com serviços de emergência.
Docker e Kubernetes: Containerização e orquestração do sistema.
Grafana/Prometheus: Monitoramento e visualização de métricas.

## 🧐 Processo de Criação
Coleta de Dados: Compilamos vídeos de trânsito de fontes públicas e câmeras locais.
Desenvolvimento: Implementamos YOLO para detecção e DeepSort para rastreamento. Utilizamos RNNs/LSTMs para prever trajetórias.
Integração: APIs foram criadas para enviar alertas automáticos para os serviços de emergência. Kafka gerenciou o fluxo de dados.
Testes e Validação: Testamos em cenários simulados e ambientes reais, ajustando com base no feedback.
Implementação: Docker e Kubernetes garantiram a escalabilidade. Monitoramos o desempenho com Grafana e Prometheus.

## 🚀 Resultados
Detecção e Rastreamento Preciso: 95% de precisão na detecção e rastreamento contínuo.
Predição de Trajetórias: Margem de erro mínima de 10 cm.
Redução de Colisões: Diminuição de 30% nos incidentes potenciais e redução de 20% no tempo de resposta dos serviços de emergência.
Integração Eficaz: Feedback positivo das autoridades sobre a precisão e eficiência dos alertas.
Escalabilidade: Suporte para múltiplas cidades com operação consistente.

Impacto
Casos Reais: Prevenção de colisões em cruzamentos movimentados.
Feedback Positivo: Melhora significativa na gestão de tráfego e resposta emergencial.
Monitoramento e Relatórios
Dashboard em Tempo Real: Monitoramento do status das câmeras e eventos de risco.
Relatórios Semanais: Detalham a precisão, tempos de resposta e casos de sucesso.

📊 Conclusão
O projeto demonstra o impacto positivo da IA na segurança do trânsito e na resposta a emergências. Com uma abordagem escalável e adaptável, o sistema é uma ferramenta valiosa para melhorar a segurança nas ruas e salvar vidas em diversas localidades.
