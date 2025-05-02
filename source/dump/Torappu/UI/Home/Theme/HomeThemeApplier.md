# HomeThemeApplier

**Namespace:** `Torappu.UI.Home.Theme`


## Fields

- `String m_elementsPropName`

- `String m_namePropName`


## Methods

- `Void _TryInitDefaultElmData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home.Theme
public class HomeThemeApplier : UIStylerApplier`1
{
	private List`1 _heightList; // 0x20
	private String m_elementsPropName; // 0x28
	private String m_namePropName; // 0x30
	private IHomeThemeElemBase[] m_elements; // 0x38
	private Dictionary`2 m_elmDataDic; // 0x40
	private Dictionary`2 m_defaultElmDataDic; // 0x48
	private static DelegateBridge __Hotfix0__TryInitDefaultElmData; // 0x0
	private static DelegateBridge __Hotfix0_OnApplyStyle; // 0x8
	private static DelegateBridge __Hotfix0__GetAllElements; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x284e15c VA: 0x7594e6615c
	private Void _TryInitDefaultElmData() { }
	// RVA: 0x284e4d8 VA: 0x7594e664d8
	protected override Void OnApplyStyle(HomeTheme theme) { }
	// RVA: 0x284ec60 VA: 0x7594e66c60
	private IHomeThemeElemBase[] _GetAllElements() { }
	// RVA: 0x284ecf4 VA: 0x7594e66cf4
	public Void .ctor() { }
}
```