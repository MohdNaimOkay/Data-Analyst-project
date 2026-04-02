How does stress level affect sleep quality?
<img width="454" height="432" alt="Screenshot 2026-03-31 213010" src="https://github.com/user-attachments/assets/b500608c-418e-4202-9453-b5b9a696e043" />


Which occupation has the highest and lowest average sleep duration?

```sql
select occupation, round(avg(sleep_duration_hrs),2) as "sleep Hours per day"
from health_dataset
group by occupation 
order by avg(sleep_duration_hrs) desc
```


<img width="389" height="447" alt="image" src="https://github.com/user-attachments/assets/1b287b5c-27dd-4c59-a94f-4bbf40c7ed39" />

Does screen time before bed impact sleep quality?
<img width="523" height="430" alt="image" src="https://github.com/user-attachments/assets/bed87fd1-977a-48ee-8347-e55539a7d7f0" />

