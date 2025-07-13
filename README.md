# HTML and CSS

# CSS

Function:
CALC,MIN,MAX,CLAMP

Ex: max-width: calc(800px - 2rem); =768
=> In above relative units('2rem') will be converted to absolute units(px).

=> max-width: min(700px, 80%,30rem);
In above case it will take the smallest one.

=> max-width: max(700px, 80%,30rem);
In above case it will take the largest one.

=> max-width: clamp(700px, 90%,900px);
In above case width never be less than smaller and greater than largest.
