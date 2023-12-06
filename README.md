### FL4PPMIC (Federated Learning for Privacy-Preserving Medical Image Classification)

**Overview of the Project:**
FL4PPMIC (Federated Learning for Privacy-Preserving Medical Image Classification) is a pioneering project to develop a deep neural network for medical image classification. This project leverages Federated Learning (FL) to ensure privacy preservation in handling sensitive medical data. The primary goal is to create a reliable and efficient model that addresses privacy concerns while maintaining high accuracy in medical image classification.

**Description of the Dataset:**
The project utilizes the "SIIM-ISIC Melanoma Classification" dataset, accessible on Kaggle. This dataset comprises dermatoscopic images, including benign and malignant lesions, making it an ideal choice for melanoma detection tasks in medical image classification.

**Objectives and Expected Deliverables:**
- Implement a Federated Learning framework tailored for medical image classification.
- Ensure privacy preservation during model training.
- Adapt local interpretability techniques to the federated model.
- Deliver a high-performance and interpretable model.
- Provide complete source code with documentation, a comprehensive PowerPoint presentation, and a detailed report of the methodology, results, and findings.

## License
Released under an MIT license. See the [LICENSE](./LICENSE) file and https://opensource.org/licenses/MIT

## Contributing

### Process

We use a fork-and-PR process, also known as a triangular workflow. This process is relatively common in open-source projects. Here's the basic workflow:

1. Fork the upstream repo to create your repo. This repo is called the origin repo.
2. Clone the origin repo to create a working directory on your local machine.
3. Work your changes on a branch in your directory, then add, commit, and push your work to your origin repo.
4. Submit your changes as a PR against the upstream repo. You can use the upstream repo UI to do this.
5. Maintainers review your changes. If they ask for changes, you work on your origin repo's branch and then submit another PR. Otherwise, if no changes are made, the branch with your PR is merged to the upstream's main trunk, the main branch.

When you work in a triangular workflow, you have the upstream repo, the origin repo, and then your working directory (the clone of the origin repo). You do a `git fetch` from upstream to local, push from local to origin, and then do a PR from origin to upstream.

If this workflow is too much to understand to start, that's ok! You can use GitHub's UI to change to autoset to do most of this process. We want you to know how the process works before proposing a change.

Thank you for your contributions; we appreciate you!

### Questions?

The easiest way to get our attention is to comment on an existing or open a new [issue][].

[issue]: https://github.com/smusali/fl4ppmic/issues
