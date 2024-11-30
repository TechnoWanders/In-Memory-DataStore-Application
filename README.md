This Project is  a simple implementation of a Redis server in Go. It is designed to support a variety of basic Redis commands, providing a lightweight alternative to the full Redis server for learning and experimentation purposes.

## Running the Server

To run the server, execute the following command:

./start_server.sh

This script will compile the Go code and start the Redis server.

## Supported Commands

The server currently supports the following Redis commands:

### Basic Commands

-   `PING`: Returns PONG.
-   `ECHO <message>`: Returns the input string.
-   `SET <key> <value>`: Sets a key to a value.
-   `GET <key>`: Gets the value of a key.
-   `INCR <key>`: Increments the integer value of a key.
-   `INFO`: Returns information about the server.
-   `KEYS <pattern>`: Returns all keys matching a pattern.
-   `TYPE <key>`: Returns the type of a key.

### Stream Commands

-   `XADD <stream> <id> <field> <value>`: Adds a message to a stream.
-   `XRANGE <stream> <start> <end>`: Gets a range of messages from a stream.
-   `XREAD STREAMS <stream> <id>`: Reads messages from a stream.


### Transaction Commands

-   `MULTI`: Starts a transaction.
-   `EXEC`: Executes a transaction.
-   `DISCARD`: Discards a transaction.

### Server Configuration Commands

-   `REPLCONF <option> <value>`: Configures replication.
-   `PSYNC <replicaid> <offset>`: Partial synchronization.
-   `WAIT <numreplicas> <timeout>`: Blocks until the specified number of replicas acknowledge the write.

## GROUP NO : 61
## MEMBERS  :
    NAVEEN PAUDEL
    NIKHIL SAHU 
    PANSHUL KHURCHWAL 

