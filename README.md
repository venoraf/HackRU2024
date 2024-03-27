# MUSE - HackRU Project

Welcome to our HackRU project discussion forum. This repository is dedicated to developing an interface that leverages the MUSE EEG headband to control applications with brain activity.

## Project Overview

Our goal is to utilize the MUSE EEG headband to detect concentration levels in real-time and translate them into actions in various applications, such as automating the Chrome Dino game based on the user's focus.

## Repositories

We are building upon the work of existing repositories to interface with the MUSE EEG headband and stream data in real-time:

- [muse-lsl](https://github.com/alexandrebarachant/muse-lsl/)
- [BlueMuse](https://github.com/kowalej/BlueMuse)
- [pylsl](https://github.com/chkothe/pylsl) for streaming real-time EEG data.

## MUSE Manual

For detailed information on operating the MUSE EEG headband, refer to the [MUSE User Guide](https://bio-medical.com/media/supportmuse-brain-sensing-headband-user-guide.pdf).

## Device Connection

We successfully connected to the MUSE device with the following identifier:
`Muse-3E67, MAC Address 00:55:DA:B3:3E:67`.

## EEG Data Visualization

![Agora Hills Figure 1](Agora_Hills_Figure_1.png)

The attached figure `Agora_Hills_Figure_1.png` demonstrates a sample EEG data output with each line representing the electrical activity from different electrodes placed on the scalp. Here's a brief on the label conventions:

- `TP9`, `TP10`: Represent electrode locations in the temporal regions of the brain.
- `AF7`, `AF8`: Indicate frontal electrode sites near the prefrontal areas.
- `Right AUX`: Refers to an auxiliary channel on the right side.

Each label is followed by the signal amplitude in microvolts (µV), indicative of the EEG signal strength at that location.

## Contributions

We welcome contributions from the community. Please feel free to fork the repo, create feature branches, and submit pull requests for review.

## Discussion

For queries, discussions, and collaboration, please use the Issues section of this repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

Special thanks to the authors and contributors of the [muse-lsl](https://github.com/alexandrebarachant/muse-lsl/), [BlueMuse](https://github.com/kowalej/BlueMuse), and [pylsl](https://github.com/chkothe/pylsl) repositories.
