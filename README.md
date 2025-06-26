# argvi

## Structure

- key : value pairs
  - value can have a type
  - flags are boolean values

## Handled input

Input is a string

- Flags

```
--verbose
-v
--daemon
-d
-vd // combined
```

- One-to-one

```
--workers 1
-w 1
--workers=1
-workers=1
```

- One-to-many

```
--gpus 0 1
-g 0 1
--gpus=0,1
-gpus=0,1
```
