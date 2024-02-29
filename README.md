# AffineTransformation

 Affine transformations are a fundamental concept in computer vision and image processing. They refer to a series of geometric operations that preserve straight lines and the parallelism of lines when applied to an image.

These transformations include translation (shifting the image along the x and y axes), rotation, scaling, and shearing. Each of these operations can be represented by a matrix, and combining them allows for efficient manipulation of images.

1. Translation: This involves shifting all points in an image by a specified distance along the x and y axes. The transformation is represented by a 2x3 matrix.

  ![image](https://github.com/Sneha-Pulse/AffineTransformation/assets/72751097/65d8bce2-3164-4be9-8f36-0464bed9a866)


3. Rotation: This operation involves rotating an image by a specified angle around a given point. The transformation is described by a 2x2 rotation matrix.

   ![image](https://github.com/Sneha-Pulse/AffineTransformation/assets/72751097/c54ca65d-26bf-4d16-a224-acd8d4b4db0c)


5. Scaling: Scaling changes the size of the image. It can be uniform (scaling in both x and y directions equally) or non-uniform (scaling by different factors along x and y). Scaling is represented by a 2x2 matrix.

  ![image](https://github.com/Sneha-Pulse/AffineTransformation/assets/72751097/7c0920ef-f7d2-4ec8-8c77-0d52444e8f77)


7. Shearing: Shearing distorts the shape of the image by shifting each point in a given direction by an amount proportional to its distance from an axis. This can be represented by a 2x3 matrix.

![image](https://github.com/Sneha-Pulse/AffineTransformation/assets/72751097/84b9a501-2bad-44e2-aa04-0c909a4ded8f)


Affine transformations are widely used in computer vision for tasks such as image registration, object detection, and image stitching. Applications of affine transformations include aligning images, correcting distortions, and transforming images to match a particular perspective.

In summary, affine transformations in computer vision encompass a set of operations that can modify the position, orientation, and scale of an image while preserving parallelism and straight lines. They are crucial for various image processing tasks and form the basis for more complex transformations in computer vision algorithms.  
