# vigia

Vigia externo dos serviços do Grupo Rios. Roda no GitHub Actions a cada 10 minutos, fora da casa e
fora da Hostinger, e avisa no ntfy quando o Radar, a Ponte ou o cérebro da Bia param de responder
(e quando voltam). Só consulta endereços públicos; o tópico do ntfy fica no secret `NTFY_URL`.

Estado: o vigia avisa só na troca (caiu / voltou). Um commit por mês mantém o agendamento ativo.
