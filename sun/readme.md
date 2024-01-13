# Weather Forecast CLI Application

This is a simple command-line application written in Go that fetches weather forecast information using the WeatherAPI.

## Prerequisites

- [Go](https://golang.org/dl/) installed on your machine.

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/AbhayGRT/Developing-a-Kubernetes-CI-CD-Workflow-with-GitLab-and-Helm-for-a-Golang-Application.git
    # if you want to rename your folder name simply use this command
    sudo mv your-repo Developing-a-Kubernetes-CI-CD-Workflow-with-GitLab-and-Helm-for-a-Golang-Application
    cd your-repo
    ```

2. Install dependencies:

    ```bash
    go get github.com/fatih/color
    ```

3. Get your API key:

    - Visit [WeatherAPI](https://www.weatherapi.com/) to obtain your API key.

4. Add your API key to `main.go`:

    - Open `main.go` and replace the placeholder `<your-api-key>` with your actual API key.

5. Run the application:

    ```bash
    go run main.go
    ```

    By default, the application uses a specific city. To specify a different city, run:

    ```bash
    go run main.go <city-name>
    ```

6. Verify the output. If everything is working fine, you should see the weather forecast details.

## Building the Application

7. To build the application:

```bash
go build
```

8. To make it accessible from anywhere:

```bash
sudo mv your-repo /usr/local/bin
```

9. Now, you can run the application from anywhere using:

```bash
your-repo
```

10. To specify a different city:

```bash
your-repo <city-name>
```

