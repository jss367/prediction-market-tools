# Manifold Probability Sum

This repository hosts a single-page web app that fetches the current probabilities for a Manifold Markets question and displays the sum. It is designed to be deployed as a static site (e.g., GitHub Pages).

## Usage

1. Paste the full URL of a Manifold market into the "Market URL" field.
2. (Optional) Enter the sum you expect the probabilities to add up to (for example, 1 for mutually exclusive outcomes or 16 for NBA playoff spots).
3. Click **Compute** to fetch the market details and calculate the sum.

For multiple-choice markets, the page lists each answer and its probability along with the total. Binary markets show the current YES/NO percentages. Numeric markets do not expose per-answer probabilities, so the sum is not applicable.

The app uses the public Manifold Markets API and requires no server-side components.
