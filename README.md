# TODOS

- SchoolYear:
- Sincronização Automática de student_count em Enrollment
- Cache para getCurrentSchoolYear e getCurrentSchoolPeriods em School
- invalidar cache de School
- Implementar Observers para cálculos automáticos de attendance_percentage
- Implementar Cache para métodos como getActiveStudentsCount()
- Adicionar Indexes nas migrations para campos frequentemente consultados


```json
// TODAS AS DISCIPLINAS
[
  { "code": "AR-2025", "name": "Arte" },
  { "code": "CI-2025", "name": "Ciências" },
  { "code": "EF-2025", "name": "Educação Física" },
  { "code": "EM-2025", "name": "Empreendedorismo" }
  { "code": "ER-2025", "name": "Ensino Religioso" },
  { "code": "GE-2025", "name": "Geografia" },
  { "code": "HI-2025", "name": "História" },
  { "code": "LI-2025", "name": "Língua Inglesa" },
  { "code": "LP-2025", "name": "Língua Portuguesa" },
  { "code": "MA-2025", "name": "Matemática" },
]
```
```json
// DADOS FINANCEIROS DO PROFESSOR
{
    "bank_name": "Bradesco",
    "agency": "1234",
    "account": "4321-0",
    "account_type": "poupança",
    "pix_key": "email@exemplo.com"
}
```
```json
// DADOS DO RESPONSÁVEL
{
    "name": "",
    "email": "",
    "phone": "",
    "relationship": "",
}
```