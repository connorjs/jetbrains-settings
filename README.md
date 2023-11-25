# JetBrains IDE Settings

Welcome to my JetBrains IDE settings.

## Not used

> **Important**
>
> I have switched to JetBrains Settings Sync instead (unfortunately).

Unfortunately, this approach did not work as well as I hoped.
I will wait for better repository integration in Settings Sync,
but, for now, I will use JetBrains server settings sync (with limited syncing).

## Instructions

### Importing these settings

1. Download `settings.zip`

2. File > Manage IDE Settings > Import Settings...

3. Select the zip file.

### Update this repository

1. File > Mange IDE Settings > Export Settings...

2. Uncheck all, then select the following.
   - DefaultFont
   - IgnoredPluginSuggestions
   - UI Settings, ProjectViewFileNesting
   - com.kagof.intellij.plugins.pokeprogress.configuration.PokemonProgressState

3. Click **OK** and then **Overwrite**

4. Export to this repository. _Git ignores the `settings.zip` file._

5. Unzip and verify the diff.

   **macOS**

   ```shell
   unzip -o settings.zip -d settings
   ```

6. If the diff is not expected, re-run export.
