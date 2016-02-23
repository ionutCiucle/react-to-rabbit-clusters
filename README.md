# react-to-rabbit-clusters
A small React/Node app that interacts with a RabbitMQ server. It contains <i>Producer</i> and <i>Consumer</i> classes, which encapsulate the 
<strong>amqplib</strong> node module, that could be reused when working with RabbitMQ. <br>
Also, the uses the <strong>cluster</strong> module in order create child processes that handle messages from the queue. <br>
The <i>throttleManager</i> object can be configured in order to control the the time in which a single message is send. <br>
Babel is used for ES6 syntax and React/JSX transpiling. <br>

# Prerequisites
You need to install the RabbitMQ server (along with its own dependencies, listed on www.rabbitmq.com) before using the app. 
Next, clone the repository: <br>
<code>git clone https://github.com/ionutCiucle/cluster-rabbit.git</code>

After that, get the node modules: <br>
<code>npm install</code>

Then install the webpack bundler globally: <br>
<code>npm install webpack -g</code>

Finally, start the server (also triggers some gulp tasks - bundling with webpack and transpiling with Babel): <br>
<code>npm start</code>


