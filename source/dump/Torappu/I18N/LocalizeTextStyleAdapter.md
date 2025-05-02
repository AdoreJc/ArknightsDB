# LocalizeTextStyleAdapter

**Namespace:** `Torappu.I18N`


## Fields

- `SettingType _settingType`

- `TextStyles _styleInLand`

- `TextStyles _styleJp`

- `TextStyles _styleEn`

- `TextStyles _styleKr`

- `TextStyles _styleTc`

- `Boolean m_overrideStyleInLand`

- `Boolean m_overrideStyleJp`

- `Boolean m_overrideStyleEn`

- `Boolean m_overrideStyleKr`

- `Boolean m_overrideStyleTc`

- `Text m_text`

- `Boolean m_isStyleInited`

- `TextStyles m_useStyle`


## Methods

- `Void Refresh()`

- `Void OnEnable()`

- `Void _RefreshStyles()`

- `Void _UpdateStyles(TextStyles)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.I18N
public class LocalizeTextStyleAdapter : MonoBehaviour
{
	private SettingType _settingType; // 0x18
	private TextStyles _styleInLand; // 0x20
	private TextStyles _styleJp; // 0x28
	private TextStyles _styleEn; // 0x30
	private TextStyles _styleKr; // 0x38
	private TextStyles _styleTc; // 0x40
	public Boolean m_overrideStyleInLand; // 0x48
	public Boolean m_overrideStyleJp; // 0x49
	public Boolean m_overrideStyleEn; // 0x4a
	public Boolean m_overrideStyleKr; // 0x4b
	public Boolean m_overrideStyleTc; // 0x4c
	private Text m_text; // 0x50
	private Boolean m_isStyleInited; // 0x58
	private TextStyles m_useStyle; // 0x60


	// RVA: 0x35bad34 VA: 0x7595bd2d34
	public Void Refresh() { }
	// RVA: 0x35bb198 VA: 0x7595bd3198
	private Void OnEnable() { }
	// RVA: 0x35bad48 VA: 0x7595bd2d48
	private Void _RefreshStyles() { }
	// RVA: 0x35bb1ac VA: 0x7595bd31ac
	private Void _UpdateStyles(TextStyles styles) { }
	// RVA: 0x35bb284 VA: 0x7595bd3284
	public Void .ctor() { }
}
```