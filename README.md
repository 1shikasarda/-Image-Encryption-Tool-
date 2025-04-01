# Image Encryption Tool
## *Overview*
It is a simple image encryption tool using pixel manipulation which allow users to encrypt and decrypt images by modifying pixel values through operations like swapping pixel values or applying basic mathematical transformations to each pixel. This Python script performs XOR-based encryption and decryption on images, ensuring secure transformation and recovery of the original image using a randomly generated key 🔒.

## *Tech Stack*
- *Core Libraries*:
    - Pillow (PIL) – For image handling (opening, processing, saving) 📸.
    - NumPy – For array manipulation and efficient XOR operations 🤖.

## *Key Features*
- *Image Encryption*:
    - Converts the image into a NumPy array 📊.
    - Applies bitwise XOR with a randomly generated key 🔑.
    - Saves the encrypted image 📁.
- *Image Decryption*:
    - Reverses encryption by reapplying XOR with the same key 🔓.
    - Restores the original image 📸.
- *Random Key Generation*:
    - Uses np.random.randint() to create a secure, one-time-use key matching the image dimensions.

## *Workflow*
1. *Input*: Original image (JPEG/PNG) 📁.
2. *Encryption*: XOR operation with a random key → Encrypted image 🔒.
3. *Decryption*: XOR operation on the encrypted image → Restored original 📸.
