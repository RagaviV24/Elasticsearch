# Elasticsearch


 Installation Instructions

a) Read about Elasticsearch: Getting Started with Elasticsearch.

b) Install Elasticsearch on your local machine.

c) Start the service in 8989 port instead of the default port


d)Download Employee Data set from https://www.kaggle.com/datasets/williamlucas0/employee-sample-data

· Function Definitions

Using Any of the programming language implement below functions


a) createCollection(p_collection_name)

b) indexData(p_collection_name, p_exclude_column): Index the given employee data into the specified collection, excluding the column provided in p_exclude_column.

c) searchByColumn(p_collection_name, p_column_name, p_column_value): Search within the specified collection for records where the column p_column_name matches the value p_column_value.

d) getEmpCount(p_collection_name)

e) delEmpById(p_collection_name, p_employee_id)

f) getDepFacet(p_collection_name): Retrieve the count of employees grouped by department from the specified collection.

· Function Executions


· Once the functions are implemented, execute the functions in the given order with the parameters mentioned and capture separate full screenshots for each step mentioned below
a) Var v_nameCollection = ‘Hash_<Your Name>’

b) Var v_phoneCollection =’Hash_<Your Phone last four digits>’

c) createCollection(v_nameCollection)

d) createCollection(v_phoneCollection)

e) getEmpCount(v_nameCollection)

f) indexData(v_nameCollection,’Department’)

g) indexData(v_ phoneCollection, ‘Gender’)

h) getEmpCount(v_nameCollection)

i) delEmpById (v_ nameCollection ,‘E02003’)

j) getEmpCount(v_nameCollection)

k) searchByColumn(v_nameCollection,’Department’,’IT’)

l) searchByColumn(v_nameCollection,’Gender’ ,’Male’)

m) searchByColumn(v_ phoneCollection,’Department’,’IT’)

n) getDepFacet(v_ nameCollection)

o) getDepFacet(v_ phoneCollection)

