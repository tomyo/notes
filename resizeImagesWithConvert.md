Using convert command from magisck to resize all files in current folder

By default mantains aspect ratio, so it will shrink proportionally until it fits to given dimentions.

```sh
WIDTH=400
OUTPUT_FOLDER_NAME="$WIDTH"w
mkdir "$OUTPUT_FOLDER_NAME"
for photo in *.jpg;
do
  magick convert "$photo" -resize "$WIDTH"x"$WIDTH" ./$OUTPUT_FOLDER_NAME/$OUTPUT_FOLDER_NAME-$photo;
done
```
