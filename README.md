# Patterson Distributor Database & Submittals

JSON file created for distributor.pattersonsingapore.com.

Format for JSON:
{
	CO: String - represent CO#
	projectRef: String - project reference
	dateEntered: Date - follow OA order entered date
	documents: [
		{
			name: String (refer to documentation),
			dateAdded: Date (date file was added into system),
			link: String (google link for direct download)
		}, etc
	]
}

To download the google file directly from google drive: 
1. Share the file (get the link)
Get the FILE_ID:
- https://drive.google.com/file/d/FILE_ID/edit?usp=sharing
2. https://drive.google.com/uc?export=download&id=FILE_ID
