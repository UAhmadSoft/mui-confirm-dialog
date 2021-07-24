# mui-confirm-dialog

## Confirm Dialog Box using Material UI

### Usage

```
  import { ConfirmDialog } from 'mui-confirm-dialog'

  const ExampleComponent = () => {
    const [open, setOpen] = useState(true)

    const toggleDialog = () => {
    setOpen((st) => !st)
    }

    const onSuccess = () => {
    console.log('success')
    toggleDialog()
    // Do Anything on Success
    }

    return (
    <ConfirmDialog
            open={open}
            toggleDialog={toggleDialog}
            dialogTitle='Perform This Action ?'
            success={onSuccess}
          />
    )
  }
```

### Props

- open
- toggleDialog
- dialogTitle
- success

### Author

- UAhmadSoft
