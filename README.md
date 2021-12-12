# Nginx run in kind

## Simples arquivos de manifesto .yaml para rodar nginx no kind

### Como utilizar
1. Utilize o arquicvo kind.yaml para criar um cluster com kind
  - kind create cluster --config=kind.yaml
2. Aplique os manifestos para criar o deployment e o service
  - kubectl apply -f .
  
  :upside_down_face:
