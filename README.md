# ![LOGO](logo.png) Computer Vision Client **flow**ground Connector

## Description

A generated **flow**ground connector for the Computer Vision Client API (version 2.0).

Generated from: https://api.apis.guru/v2/specs/microsoft.com/cognitiveservices-Ocr/2.0/swagger.json<br/>
Generated at: 2019-06-11T18:14:41+03:00

## API Description

The Computer Vision API provides state-of-the-art algorithms to process images and return information. For example, it can be used to determine if an image contains mature content, or it can be used to find all the faces in an image.  It also has other features like estimating dominant and accent colors, categorizing the content of images, and describing an image with complete English sentences.  Additionally, it can also intelligently generate images thumbnails for displaying large images effectively.

## Authorization

Supported authorization schemes:
- API Key
## Actions

### Use this interface to get the result of a Read operation, employing the state-of-the-art Optical Character Recognition (OCR) algorithms optimized for text-heavy documents. When you use the Read File interface, the response contains a field called "Operation-Location". The "Operation-Location" field contains the URL that you must use for your "Read Operation Result" operation to access OCR results.

#### Input Parameters
* `mode` - _required_ - Type of text to recognize.
    Possible values: Handwritten, Printed.

### This interface is used for getting OCR results of Read operation. The URL to this interface should be retrieved from "Operation-Location" field returned from Batch Read File interface.

#### Input Parameters
* `operationId` - _required_ - Id of read operation returned in the response of the "Batch Read File" interface.

### Recognize Text operation. When you use the Recognize Text interface, the response contains a field called 'Operation-Location'. The 'Operation-Location' field contains the URL that you must use for your Get Recognize Text Operation Result operation.

#### Input Parameters
* `mode` - _required_ - Type of text to recognize.
    Possible values: Handwritten, Printed.

### This interface is used for getting text operation result. The URL to this interface should be retrieved from 'Operation-Location' field returned from Recognize Text interface.

#### Input Parameters
* `operationId` - _required_ - Id of the text operation returned in the response of the 'Recognize Text'

## License

**flow**ground :- Telekom iPaaS / microsoft-com-cognitiveservices-ocr-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
