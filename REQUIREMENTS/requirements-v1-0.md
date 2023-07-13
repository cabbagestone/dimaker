# Dimaker Project Overview

## Overview Overview

This project overview serves as the spec and requirements for the first version of Dimaker. It includes high level feature descriptions, project details, and user details.

### Project Description

Dimaker aims to be a streamlined decision assistance software for an individual or small group. While there are a large number of decision making softwares out there on the web, a lot of the best ones are corporate focused. Realistically, the featureset of the company focused decision making softwares isn't all that helpful to a single individual anyways. As for the existing decision making software, I think it lacks an element of user friendliness. I want the decisions making process on Dimaker to be as thorough or simple as the user wants it to be. I also want to eventually have informed decisions, where the decisions can rely upon each other, and rely upon values and goals that you can set in Dimaker. I place a strong emphasis on incrementalism in my own life, since I'm doing so many things, and like it when I can delegate a small amount of extremely effective time to a project each day, over grinding on the project for long periods of time intermittently.

### Purpose of the Project and Users

Half of the purpose of the software is simply to grow as a developer. I do want to use the resulting software, and I enjoy using software that I create - but more than that, I want to experience a well designed developer experience. You can read more about my journey on [my blog](https://blog.arch-texture.com/). Because the intended audience is myself, I'm going to be designing with a smaller scope in mind. If the software picks up a higher user count, I will deal with that scaling when it comes.

### Feature Overview

I want the Dimaker experience to be focused on streamlining the decision making process. Dimaker is performing it's function when the experience is less about the software, and more about exploring the decision that the user is making. All features should be very action oriented and unbloated. While customization should be in easy reach, I want the default settings to be ultimate simplicity.

Each decision, in it's most basic form, is a pros and cons list for courses of action that can be taken within the context of a decision. These should be easy to compare and consider, and the UI should make comparisons extremely simple for the user to see.  

When a user logs into the system, they should have immediate access to relevant information on their existing decisions, as well as a lightning quick way to create a new decision.

Ideally the user could create a decision, it's associated candidates for courses of action, and the factors to be considered all within the course of minutes.

The initial version of the software will rely upon the users inherent decision making capacity, merely serving as an organized way to present data. Future features will allow more technical comparisons of decision factors.

### Dimaker values

- Customizeable complexity
- Incrementalism
- Simple development workflow
- Transparency and Clarity

## Dimaker Features and Use Cases

### Decision Creation Wizard

#### Description

The user should be able to create a high level decision overview within minutes.

#### Functional Requirements

- The user should be able to quickly enter the Wizard quickly and conveniently within the software.
- The Wizard should have four steps: 
1. Defining the Decision - The general overview of what needs to be decided
2. Defining the Action Candidates - What the possible courses of action are
3. Defining the Decision Factors - Considerations for making the decision
4. Defining the Candidate Factors - The specifics of each action candidate
- The Wizard should finish by taking the user to the Decision View Page

### Decision Database

#### Description

The user should be able to see all decisions created in the past, and open them, and have basic interactivity

#### Functional Requirements

- The User should be able to access this screen with ease
- The User should be able to search decisions based on decision name
- The User should be able to select a decision to view it's details
- The User should see basic decision details in the table 

### Decision View Page

#### Description

The User should be able to open a decision and see all of it's details clearly

#### Functional Requirements

- The User should be able to see a decisions title clearly
- The User should be able to clearly see a table where the columns represent courses of action, and the rows represent factors, and the intersection is the details to be considered for each.
- The User should be easily able to navigate, scroll, and see cells for large tables.

### User Account Feature

#### Description

The user should be able to sign into and manage their account with ease.

#### Functional Requirements

- The User should be able to create an account with a Username and Password
- The User should be able to sign into the app with their Username and Password
- The User should be able to edit their Password at any time
- The User should have security limitations imposed upon their password.

## Dimaker Constraints

### Development

Clearly, I'm just one dude. Furthermore, I'm not a senior developer quite yet. Enough said.

### Resources

I don't intend to put very many resources into hosting the software, in fact it will probably just be self hosted for quite a while. I also don't have infinite time for development and maintenance.

### Legal

I might need to change the name lol. I'm pretty sure it's not an issue for a project of this scale, but it's something to consider. 

I also haven't yet picked a license for the software. This should come soon.

## Dimaker Assumptions

I'm assuming, primarily, that nobody is going to need or use the software right away haha. I'm also assuming that I will be the sole contributor for a considerable amount of time.

## Dimaker Possible Future Requirements

### Decision Creation Wizard

- Autosaving Wizard
- Responsive Progress Reporting
- Optional Complexity in creation

### Decision Database

- Searching by more than just decision name
- Decision actions from this page
- Advanced filters and sorting

### Decision View Page

- Decision actions based on functionality below
- Factor and Candidate filtering/searching
- Different view formats
- Decision timeline

### Decision Functionality

- Decision Due Dates
- Decision Factor comparisons
- Interconnected Decisions
- Decision sub-decisions (Choosing preferences between options based on candidate factors)

### User Account

- Linking an email
- Password reset
- Deleting an account

### Future Features

- Values (Considerations for related factors)
- Goals (Considerations for related factors)
- Decision Templates
- Decision Calendar
- Sharing decisions between users

## Dimaker Entities and Domain Language

- Decisions
- Factors
- Candidates
- Candidate Factors

### Decisions

Decisions represent a set of data necessary to determine an appropriate course of action.

### Factors

Factors represent the parts of a decision that should be considered when deciding which action to take.

### Candidates

Decision candidates represent the potential options present within a decision.

### Candidate Factors

An Aspect is the intersection between a candidate and a factor - what describes the factor for this candidate?


