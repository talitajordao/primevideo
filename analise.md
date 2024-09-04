## Análise Realizada
***

***
```sql
SELECT 
    user_id,
    location,
    COUNT (membership_start_date) AS assinaturas
    FROM amazon_prime_users
    GROUP BY membership_end_date
    ORDER BY assinaturas DESC
```
