# Internet speed test diagnostics
Docker container which takes a speed test using Ookla on a set interval, and runs a continuous ping check to ensure constant connectivity.
All data is output in a fault tolerant way to a CSV for easy parsing in spreadsheet software.

Uses Alpine base container, and Python to parse ping and speedtest-cli.
