The API documentation contains information on services the API provides and explains how to use and integrate with the API. It includes information on resources, methods, and parameters, supported by tutorials and examples.

An API reference manual covers the information required to work with the API, with details about the use cases, structure, functions, classes, return types, arguments, and more. It contains a path to API, and operation information, such as authentication methods, parameters, request bodies, response bodies, and headers.

# Overview

Explain why this API is needed and include use cases. 

# Getting Started

The Getting Started section and tutorials provide guidelines for good sample code. They talk about tools you can use to call REST APIs, as well as give you hands-on exercises to try those tools. 

The Getting Started section leads people through a simple task for web APIs. This might cover user registration and login, getting an app key authorization, and doing something simple. 

## Key Concepts

APIs typically have important concepts that you may need to describe. This usually depends on the area of knowledge around what the API does. For each concept, write a paragraph or two explaining what it is and how it works. For example, for a learning management system, key concepts might be roles, in other words, the teacher, student, administrator, etc. An online banking system might have concepts like accounts and transactions. 

## Architecture

The Architecture section provides a high-level overview of the API components. You need to explain the major pieces of the API, and then explain how all those pieces fit together. You might want to include an architecture diagram. 

## Workflow and examples

Workflow outlines the sequence of API interactions. It's pretty common that when you want to do a typical task with an API, you have to make several API calls. The workflow describes the order of these calls. For example, a workflow for playing a song from a playlist involves first getting a list of all playlist and their IDs. The user will then select the playlist. Then you make another call to get the list of songs and IDs for that playlist. You specify the playlist with the ID, then the user selects a song. Finally, you make a third call to request the sound file for that song using a song’s ID. 

You can provide examples similar to the one below.

**Example**: Sometimes a mobile carrier pushes notifications related to their service. An API can be designed to collect information on how subscribers react to notifications. 

## Diagrams

Diagrams can be useful. The first type is an architecture diagram, which shows how the various pieces of the API fit together. The second type is a workflow diagram, which shows the order of calls that are made. It shows which systems are making API calls to which other system.

## Authentication 

The authentication section contains data required to allow the user to authenticate and login settings. It may provide default user names and passwords. 

## Tutorials

Tutorials should cover tasks that are commonly done with the API. Here are some examples. For a learning management system API. You might have a tutorial on adding a student to a course. For an online banking API, you might have a tutorial on how to retrieve account information. For a photo-sharing API, you might have a tutorial on uploading an image. 

Tutorials have the same structure as the Getting Started section. It provides step-by-step instructions and sample HTTP requests or programming code that developers can copy and paste. Put in as many screenshots as you can, but only if they really show something. 

­­­­­

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

# Common sections in the REST API documentation

The following are the sections usually provided in API reference documentation.

## Resource description 

*![img](file:///C:/Users/maria/AppData/Local/Temp/msohtmlclip1/01/clip_image002.png)*

This section describes how to use resources. 

Information of various types returned by an API is referred to as “Resources”. The resource is usually described in a few short sentences. 

A resource is a RESTful subset of an endpoint. An endpoint is a location where a service can be accessed. Resources have various methods for every endpoint. A resource description usually indicates endpoints required to access the resource.

An API uses a request method and a response method. API methods describe the process of submitting a client’s request to access the service at the backend and to define the responses that the client receives in return. 

## Endpoints and methods 

![img](file:///C:/Users/maria/AppData/Local/Temp/msohtmlclip1/01/clip_image004.png)

This section describes how to use endpoints and provides their brief description. 

The endpoints define how the resource is accessed. The method describes the available interactions with the resource. The most-commonly-used HTTP methods are GET, POST, PUT, PATCH, and DELETE. A resource has associated endpoints that show the end portion of a resource URL path.

## Parameters 

**![img](file:///C:/Users/maria/AppData/Local/Temp/msohtmlclip1/01/clip_image006.png)**

Parameters sent with the endpoint specify the response format, such as JSON or XML. 

REST APIs have several types of parameters:

- Header     parameters: The request header includes parameters related to     authorization that are common across all endpoints. 
- Path parameters: Parameters that are appended to     the endpoint URL, before the query string ( ? ). 
- Query string parameters: Parameters included in     the query portion of the endpoint, after the ?.

The parameters are often grouped by their types. 

## Request example

**![img](file:///C:/Users/maria/AppData/Local/Temp/msohtmlclip1/01/clip_image008.png)**

It is recommended to provide example requests and responses to help your API’s consumers understand how to use it and what to expect in response. Request examples describe how the API responds to a request in various situations. Provide a few parameter configurations. Include code snippets that demonstrate the request in various languages.

## Response example and schema

**![img](file:///C:/Users/maria/AppData/Local/Temp/msohtmlclip1/01/clip_image010.png)**

The response schema contains the description of the response. It is a comprehensive way to document the response describing each property that could be returned, the contents of the property, the structure, and the data format.

The response example shows a response to the request described in the previous section. The response schema describes elements of the response. 

The sample response should contain parameters matching the ones in the request example. Provide a few configurations of parameters.

 

 

 

 