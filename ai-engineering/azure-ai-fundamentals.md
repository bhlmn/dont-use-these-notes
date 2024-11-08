# Azure AI Fundamentals (AI-900) Notes

## Azure AI Services

#### How do Azure AI services improve speed-to-market for AI solutions?

- They are prebuilt models that are ready to use
- They are accessed through APIs
- They are available on Azure

#### How are Azure services provisioned?

To provision an Azure service, you need to have:
- An Azure subscription (account)
- A resource group

#### What are the two types of Azure service resources, and when might you use each?

- A **single-service resource** provides access to a single Azure service. This is a good strategy when you only need one Azure resource for a project or when you want to see cost information separately.
- A **multi-service resource** provides access to many Azure services with a single key and endpoint. With this strategy all services are billed together. This is helpful when you need several Azure services or are exploring capabilities.

#### What are the different service studio interfaces, and what do they do?

- Vision Studio let's you explore Azure Vision capabilities
- Language Studio – Language services
- Speech Studio – Speech to text and text to speech
- Content Safety Studio – Content safety functionality
- Azure AI Studio – Develop GenAI solutions and custom copilots
- Azure ML Studio – ML lifecycle and autoML

## Computer Vision

#### What resource(s) need provisioned to work with Azure AI Vision service?

Either Azure AI Vision or Azure AI Services.

#### What image analysis capabilities does Azure AI Vision offer?

- Optical character recognition (OCR)
- Generating image captions and descriptions
- Object detection
- Object tagging (multiple text keywords for the image)


#### When might you need to train your own custom vision models in Azure AI Vision?

When the built-in models don't meet your needs out of the box. You can fine tune a custom model for the following use cases. Just bring your images!

- Image classification
- Object detection

## Facial Recognition

#### What Azure AI services help with facial detection and analysis?

- Azure AI Face is the Azure service for facial detection, analysis, and recognition.
- Azure AI Video Indexer enables facial detection and identification in videos.
- Azure AI Vision offers face detection and basic face analysis.


#### What is the difference between face detection, face analysis, and facial recognition?

Facial detection is the process of identifying and locating faces in images or video. Facial analysis analyzes facial features. Facial recognition is a branch of face analysis that tries to identify known individuals based on their faces being present in images or video.

#### What facial attributes can be returned by Azure AI Face?

- Whether the face has accessories such as headwear, glasses or a mask.
- How blurred the face is.
- The orientation of the face in 3D space (its pose)
- The noise of the image
- How occluded (blocked) the face is.
- How good the image might be for facial recognition (high, medium, or low).

#### Which capabilities of Azure AI Face* *require customers to submit an intake form?

- Face identification
- Face verification – seeing if the face in an image is similar to a face in another image
- Liveness detection – to determine if an image or video is fake

#### How can you use AI Face service in a no-code way?

Play with the service in Azure Vision Studio!

### Optical character recognition

#### Which service(s) is used for OCR tasks?

Azure AI Vision and Vision Studio.

#### What text details are extracted from images with the Read API?

- One object for each page of text, including page size and orientation.
- The lines of text on a page and their contents (including the bounding polygon)
- Each word in each line (including the bounding polygon)

#### Can you use Vision Studio for OCR in production applications?
No. Vision Studio is a playground for OCR use cases and experimentation. To build an app you will need to use the Azure AI Vision SDK or REST API.


## Responsible AI

#### What are the six responsible AI principles?

AI systems should be ([source](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/strategy/responsible-ai)):

- Fair – treat everyone equally and provide the same recommendations to all individuals
- Reliable and safe
- Private and secure
- Inclusive – empower and engage everyone
- Transparent (and understandable)
- Accountable – AI systems and those that build them should be accountable and answerable.
