# Multipart-Document-Upload
This is a small project for multipart API to upload documents from webpage.

# Prerequisites
1. Visual Studio 2015 or higher
2. .NET Framework 4.7.2
3. Postman or any other API client

# API documentation
**API Url**: http://localhost:28700/api/Uploader/MediaUpload

**Body**: form-data with key : "files" of type File.

**Response**: 
```
[
    {
        "OriginalFileName": "hardik (1).jpg",
        "FileName": "202107152202047544.jpg",
        "LocalPath": "F:\\GitHub Repos\\Multipart-Document-Upload\\MultipartDocumentUploader\\Uploads\\202107152202047544.jpg",
        "PublicUrl": "http://localhost:28700/Uploads/202107152202047544.jpg",
        "Size": 1011598,
        "MimeType": "image/jpeg"
    },
    {
        "OriginalFileName": "hardik.jpg",
        "FileName": "202107152202047614.jpg",
        "LocalPath": "F:\\GitHub Repos\\Multipart-Document-Upload\\MultipartDocumentUploader\\Uploads\\202107152202047614.jpg",
        "PublicUrl": "http://localhost:28700/Uploads/202107152202047614.jpg",
        "Size": 1011598,
        "MimeType": "image/jpeg"
    }
]
```
