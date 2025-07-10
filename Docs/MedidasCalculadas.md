| TableID | Column Name | Expression                                                                        | FormatString |
| ------- | ----------- | --------------------------------------------------------------------------------- | ------------ |
| 13      | Año         | YEAR(Calendario[Date])<br>                                                        | 0            |
| 13      | Semana      | WEEKNUM(Calendario[Date], 2)  // El '2' indica que la semana empieza el lunes<br> | 0            |
| 110844  | Semana      | WEEKNUM(BD_AppMerma[FechaHora])                                                   | 0            |
