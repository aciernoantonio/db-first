# Concessionario

## Modello: Car

## Table: Cars

- id :                             BIGINT                   PK(NOTNULL, AUTOINCREMENT, UNIQUE)
- brand :                          VARCHAR(30)              NOTNULL, INDEX
- model :                          VARCHAR(30)              NULL, INDEX
- condition_class :                VARCHAR(2)               NULL, INDEX
- km :                             SMALL                    NULL, INDEX
- year :                           YEAR                     NULL, INDEX
- damages :                        TEXT                     NULL
- fuel :                           VARCHAR(20)              NULL, INDEX
- transmission :                   VARCHAR(20)              NULL, INDEX
- doors :                          TINYINT                  NULL, INDEX
