# Assignment
Fix the code so it can run succefully as:  
**Lineage:**
![Alt text](readme/lineage.png?raw=true "Lineage")

**Table fct_orders:**
![Alt text](readme/ddl.png?raw=true "Lineage")

**Sample results:**
![Alt text](readme/sample.png?raw=true "Lineage")


# Prerequisites

```bash
rm -rf myenv
# set up venv and run dbt
python -m venv myenv
source myenv/bin/activate
pip install -r requirements.txt
```

# Run dbt 

Run dbt commands as shown below:

```bash
dbt clean
dbt deps
dbt snapshot
dbt run 
dbt test
dbt docs generate
dbt docs serve
```

Go to [http://localhost:8080](http://localhost:8080) to see the dbt documentation.

# Check
```
duckcli dbt.duckdb

```

