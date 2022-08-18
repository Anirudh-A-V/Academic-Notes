# Data Model

One of the main characteristics of the database approach is to support [[Data Abstraction]] so that different users can perceive data at their preferred level of detail.

A **data model**—a collection of concepts that can be used to describe the structure of a database—provides the necessary means to achieve this abstraction.

By structure of a database we mean the data types, relationships, and constraints that apply to the data.

## Categories of Data Model
- **High-level or [[Conceptual Data Models]]**
		- Provide concepts that are close to the way many users perceive data.
- **Low-level or [[Physical Data Models]]**
		- Provide concepts that describe the details of how data is stored on the computer storage media, typically magnetic disks.
		- Concepts provided by physical data models are generally meant for computer specialists, not for end users.
- **[[Representational Data Models]]**
		- Representational data models hide many details of data storage on disk but can be implemented on a computer system directly.
		- Between above two extremes is this class of models, which provide concepts that may be easily understood by end users but that are not too far removed from the way data is organized in computer storage.