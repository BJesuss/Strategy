# Atividade Strategy - Prof. Rafaela
## Alunos:
  Breno Jesus Andrade de Oliveira: RA - 4231921291

Requisitos:

<pre style="max-height: 300px; overflow-y: auto; border: 1px solid #ddd; padding: 10px;">
1. Crie uma interface EstrategiaOrdenacao com o método ordenar(List<Integer> numeros) que cada estratégia de ordenação implementará.

2. Crie classes concretas que representem diferentes estratégias de ordenação:
- OrdenacaoBubbleSort
- OrdenacaoSelectionSort
- OrdenacaoInsertionSort

3. Cada uma deve implementar o método ordenar(List<Integer> numeros) da interface EstrategiaOrdenacao.

4. Crie uma classe ContextoDeOrdenacao que terá uma referência para um objeto do tipo EstrategiaOrdenacao. Esta classe deverá ter os métodos:
setEstrategia(EstrategiaOrdenacao estrategia): para definir qual estratégia será utilizada.
executarOrdenacao(List<Integer> numeros): que executa o método ordenar() da estratégia definida.

5. Na classe Principal, permita ao usuário escolher qual algoritmo de ordenação será usado e aplique a ordenação à lista fornecida.

</pre>
