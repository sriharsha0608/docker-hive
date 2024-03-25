# docker-hive
<h1>Hello All,</h1>
<p>This is a github repository for Apache hive using docker container.</p>
<p>This deploys hive. It uses hiveserver2 on port 10000.</p>
<p>After cloning, run the followig commands in your command prompt. </p>

<pre> docker-compose up -d </pre>
<pre>docker compose exec hive-server bash</pre>
<pre>/opt/hive/bin/beeline -u jdbc:hive2://localhost:10000</pre>

<p>Thank you</p>
