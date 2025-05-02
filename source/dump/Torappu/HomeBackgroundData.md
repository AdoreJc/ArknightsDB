# HomeBackgroundData

**Namespace:** `Torappu`


## Fields

- `String defaultBackgroundId`

- `String defaultThemeId`

- `String defaultBgMusicId`

- `Int64 themeStartTime`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class HomeBackgroundData
{
	public String defaultBackgroundId; // 0x10
	public String defaultThemeId; // 0x18
	public List`1 homeBgDataList; // 0x20
	public List`1 themeList; // 0x28
	public Dictionary`2 backgroundLimitData; // 0x30
	public Dictionary`2 themeLimitData; // 0x38
	public String defaultBgMusicId; // 0x40
	public Int64 themeStartTime; // 0x48


	// RVA: 0x349d974 VA: 0x7595ab5974
	public Void .ctor() { }
}
```