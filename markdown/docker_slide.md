<!-- Slide 2 -->
<h3 style="color: #42affa;">What is Docker</h3>
> Docker is an open platform for developing, shipping, and running applications.

> Docker provides a way to run applications securely isolated in a container, packaged with all its dependencies and libraries.


---

<!-- Slide 3 -->
<h3 style="color: #42affa;">Benefits of Docker</h3>
- Open Source
- Rapid Application Development
- Portability across Machines
- Lightweight
- Simplified Maintenance
- Microservices and Integrations
- Isolation
- Modularity
- Scalability

---

<!-- Slide 4 -->
<h3 style="color: #42affa;">Docker Engine</h3>
![Docker Engine](/img/docker_engine.png)

--

<!-- Slide 5 -->
*Docker Engine* is a client-server application with these major components:
<ul>
<li class="fragment slide-out fade-in">A server which is a type of long-running program called a daemon process (the `dockerd` command).</li>
<li class="fragment slide-out fade-in">A REST API which specifies interfaces that programs can use to talk to the daemon and instruct it what to do.</li>
<li class="fragment slide-out fade-in">A command line interface (CLI) client (the `docker` command).</li>
</ul>

---

<!-- Slide 6 -->
<h3 style="color: #42affa;">Docker Architecture</h3>
![Docker Architecture](/img/docker_architecture.svg)

---

<!-- Slide 7 -->
<h3 style="color: #42affa;">Docker Components</h3>
- Docker Daemon
- Docker Client
- Docker Registry
- Docker Objects

--

<!-- Slide 8 -->
<h3 style="color: #42affa;">Docker Daemon</h3>
- The *Docker daemon* (`dockerd`) is a server, listens for Docker API requests.
- Manages Docker objects such as images, containers, networks and volumes.

--

<!-- Slide 9 -->
<h3 style="color: #42affa;">Docker Client</h3>
- The *Docker client* (`docker`) is the primary way that many Docker users interact with Docker.
- When user runs any command, client sends these commands to `dockerd`.

--

<!-- Slide 10 -->
<h3 style="color: #42affa;">Docker Registry</h3>
- A *Docker registry* stores Docker images.
- Docker Hub and Docker Cloud are public registries that anyone can use.
- Docker is configured to look for images on Docker Hub by default.

--

<!-- Slide 11 -->
<h3 style="color: #42affa;">Docker Objects</h3>
- When you use Docker, you are creating and using images, containers, networks, volumes and other objects

--

<!-- Slide 12 -->
<h3 style="color: #42affa;">Images</h3>
- In Docker, everything is based on images.
- An image is a read-only template with instructions for creating a Docker container.
- An image is an executable package that includes everything needed to run an application--the code, a runtime, libraries, environment variables, and configuration files.

--

<!-- Slide 13 -->
<h3 style="color: #42affa;">Containers</h3>
- A container is a runnable instance of an image.
- A container is defined by its image as well as any configuration options you provide to it when you create or start it.

---

<!-- Slide 5 -->

---

<!-- Slide 5 -->

---

<!-- Slide 5 -->

---

<!-- Slide 5 -->

---

<!-- Slide 5 -->

---