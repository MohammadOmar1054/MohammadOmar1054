# Contribution snake animation

`.github/workflows/snake.yml` regenerates the contribution-graph "snake"
animation every 12 hours and pushes it to the `output` branch.

To activate it:
1. Push this repository.
2. Open the repo **Settings -> Actions -> General**, set *Workflow permissions*
   to **Read and write permissions**, save.
3. Run the **Generate Snake** workflow once manually from the **Actions** tab.
4. After the first successful run, uncomment the snake block in `README.md`.
