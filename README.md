# A Guide to Open Source

An open source manual for contributing to or maintaining an open source project.

## Finding an Open Source Project

## Contributing to an Open Source Project

## Maintaining an Open Source Project

Maintaining an open source project means engaging with users and building a strong developer community. 

### Documenting your Project

Documentation is an integral part of building an open source project. It helps users understand and interact with your project, and it helps contributors make efficient and meaningful changes.

#### Product Documentation

The first type of documentation necessary for an open source project is **product documentation**. Product documentation intends to educate both users and contributors about what is being built. This information should be placed into the project's README, which is a [markdown](https://en.wikipedia.org/wiki/Markdown) file entitled `README.md` that exists in the root directory of the project. The product documentation should cover the following:

1. What the product is and why it's important (what problems it solves, how it is better than existing solutions)
   * This is your chance to grab the attention of potential users and contributors. It should only be a few sentences long and should appear at the very beginning of your README.
2. What the future of the product is (planned maintenance, planned features)
   * For people to rely on your product, they must be confident that it will be maintained in the future. You should clearly communicate your plans for supporting different versions of your product.
   * Planned features should be listed in a roadmap. This not only demonstrates your future intent to users but could attract contributors.
3. How to use the product (installation, quick start, and common usages)
   * The installation guide should take the form of clear, concise, step-by-step instructions.
   * The quick-start guide should provide the simplest way to get the product into a working state.
   * The common usages section should provide step-by-step instructions for the most common uses of the product.
4. What one is allowed to do with the product (licenses)
   * A summary regarding how the project can be altered and redistributed should be placed in the README and should link to the license file for more detailed information

[PyTorch's README](https://github.com/pytorch/pytorch/blob/master/README.md) is an example of effective product documentation.

#### Contributor Documentation

Contributors are the lifeblood of your project, so writing good documentation for contributors is paramount. **Contributor documentation** should  be located in the project's `CONTRIBUTING.md` [markdown](https://en.wikipedia.org/wiki/Markdown) file located in the root directory of the project. It should include information related to:

1. What to know before contributing (pertinent development information)
   * This should come first and should include any overarching information that will help contributors make informed design decisions. For example, defining the scope for the project (the goals and non-goals).
2. What you're looking for in contributions
   * Unwanted contributions can happen, so indicate directly what kinds of contributions your project is looking for
3. How to contribute (finding an issue, making an effective pull request)
   * A step-by-step guide to finding an issue and finding beginner-friendly issues
   * Conventions for making pull requests in the repository -- how to write the PR description and what information to include
4. How to write an issue / report a bug
   * Conventions for creating an issue -- how to write the issue description and what information to include

### Building a Strong Developer Community

Contributors are the lifeblood of a project. An inviting, friendly, and engaging environment will encourage more contributors. This is accomplished with the following steps:

1. Encourage contributors to give feedback in a friendly manner
   * Feedback should not be personal, and comments should be patient with the other contributors
   * For example:  `Your contribution doesn’t match this project’s criteria` versus `I don’t like your contribution` 
2. Institute mentorship
   * Mentorship is an effective way of ensuring the knowledge of senior contributors is preserved while also making new contributors more comfortable
3. Create a central form of communication
   * Communication channels like mailing lists or weekly developer meetings will help contributors stay engaged with your project
