# My Tests Controller
1. shouldReturnSortedIdsWhenNoSortParameterProvided() → Indica que a ordenação ocorre quando nenhum parâmetro de ordenação é passado.
# My Tests Service
1. shouldUpdateDataWhenIdExists() → Testa se os dados são atualizados corretamente quando o ID existe no banco de dados.
2. shouldReturnCorrectIdWhenFetchingData() → Testa se o ID retornado corresponde ao esperado ao buscar dados do banco. **IMPORTANTE**
3. shouldSetIdToNullWhenInsertingNewEntity() → Garante que, ao inserir uma nova entidade, o ID seja null ou não seja enviado no corpo da requisição.
