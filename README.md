# indiceImobilizacaoPatrimonioLiquido
A imobilização do patrimônio líquido (também conhecida como imobilização do capital próprio ou pela sigla IPL) é um indicador contábil que demonstra o quanto dos recursos a empresa aplica no ativo permanente.

```
public class imobilizacaoInvestimento {
	public static void main(String[] args) {
		double ativoPermanente = 90000;
		double totalAtivo = 1300000;

		double imobilizacaoInvestimento;

		imobilizacaoInvestimento = ativoPermanente / totalAtivo;

		System.out.println("O índice calculado em Imobilização do Investimento é?  " + 
				imobilizacaoInvestimento);
	}

}
