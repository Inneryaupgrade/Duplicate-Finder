# Duplicate Finder

## Features

- Folder and drive scanning
- File size pre-filtering
- Hash-based comparison
- Duplicate groups
- Side-by-side file information
- Selection for cleanup
- Scan result export

## How It Works

1. Open the application.
2. Select the files, folders or information you want to work with.
3. Choose the required operation.
4. Adjust the available options.
5. Start the operation.
6. Review the result and output.

## Use Cases

- Cleaning large folders
- Finding duplicate downloads
- Reducing wasted storage
- Reviewing duplicate media files

## Interface

The application is designed with a practical desktop interface containing the main workspace, operation controls and a result or progress area.

The most frequently used actions should remain accessible without requiring command-line commands.

## Output

The application displays the result of each operation directly in the interface. Operations that create files should allow the user to choose or clearly see the output location.

## Performance

Long-running operations should provide visible progress and keep the interface responsive. Batch operations are handled as a queue where appropriate.

## Error Handling

When an operation cannot be completed, the application should show the affected item and a readable explanation of the problem instead of silently ignoring the error.

## Roadmap

- [ ] Core desktop interface
- [ ] Main duplicate file detection workflow
- [ ] Batch processing
- [ ] Progress and status reporting
- [ ] Error handling
- [ ] Windows release build
- [ ] Interface polish

## Requirements

- Windows desktop environment
- Sufficient storage for the files being processed
- Additional requirements may depend on the final implementation and packaged release

## Notes

The application is intended for local desktop use. Features and supported formats can be expanded as the implementation develops.
