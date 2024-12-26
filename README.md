# FreeMeshNet

FreeMeshNet is an open-source project aimed at providing free and reliable internet through a decentralized mesh network. By connecting devices directly, FreeMeshNet extends the range of internet connectivity and enhances its reliability.

## Features

- **Peer-to-Peer Communication:** Devices connect directly without relying on a central server.
- **Dynamic Routing:** Automatically finds the best path for data.
- **Self-Healing:** The network adapts to changes and failures.
- **Internet Sharing:** Share internet access among devices.
- **Load Balancing:** Distribute internet traffic evenly.
- **Security:** Encrypted connections to ensure privacy.

## Getting Started

### Prerequisites

- Python 3.8+
- Docker

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/FreeMeshNet.git
    cd FreeMeshNet
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Set up Docker containers:
    ```bash
    docker-compose up
    ```

### Usage

1. Start the mesh network:
    ```bash
    python src/start_network.py
    ```

2. Connect new devices by running the setup script:
    ```bash
    python src/connect_device.py --ip <device_ip>
    ```

3. Monitor the network:
    ```bash
    python src/monitor_network.py
    ```

## Contributing

We welcome contributions! Please read our [contributing guidelines](CONTRIBUTING.md) and our [code of conduct](CODE_OF_CONDUCT.md) for more information.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
