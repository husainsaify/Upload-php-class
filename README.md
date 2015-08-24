# Upload-php
Upload php is a simple php class which cut the lengthy file uploading process to one line

# How To Use
1. Include the Upload.php <?php include("Upload.php"); ?>
2. On form submit instantiate the Upload class <?php $upload = new Upload($_FILES['files'],"image/",100000, array('jpg','png')); ?>
3. See results <?php print_r($upload->GetResult()); ?>
