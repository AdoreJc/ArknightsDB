# HotUpdateProgressPanel

**Namespace:** `Torappu.UI.HotUpdate`


## Fields

- `GameObject _panelProgress`

- `Image _progressBar`

- `Text _textTitle`

- `Single _textLength`

- `GameObject _iconLoading`

- `GameObject _iconDownload`

- `Text _textInfo`

- `Progress m_progress`

- `String m_titleFormatCache`


## Methods

- `Void Update()`

- `Void _UpdateResourceInfo(Single, Progress)`

- `Void _UpdateProgressInfo(Single)`

- `Void _UpdateIcon(IconType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HotUpdate
public class HotUpdateProgressPanel : DataBinder`1
{
	private GameObject _panelProgress; // 0x20
	private Image _progressBar; // 0x28
	private Text _textTitle; // 0x30
	private Single _textLength; // 0x38
	private GameObject _iconLoading; // 0x40
	private GameObject _iconDownload; // 0x48
	private Text _textInfo; // 0x50
	private Progress m_progress; // 0x58
	private String m_titleFormatCache; // 0x60
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_Update; // 0x8
	private static DelegateBridge __Hotfix0__UpdateResourceInfo; // 0x10
	private static DelegateBridge __Hotfix0__UpdateProgressInfo; // 0x18
	private static DelegateBridge __Hotfix0__UpdateIcon; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x27bc03c VA: 0x7594dd403c
	public override Void OnValueChanged(HotUpdateProgressProperty property) { }
	// RVA: 0x27bc1e0 VA: 0x7594dd41e0
	private Void Update() { }
	// RVA: 0x27bc300 VA: 0x7594dd4300
	private Void _UpdateResourceInfo(Single curProg, Progress progress) { }
	// RVA: 0x27bc518 VA: 0x7594dd4518
	private Void _UpdateProgressInfo(Single curProg) { }
	// RVA: 0x27bc144 VA: 0x7594dd4144
	private Void _UpdateIcon(IconType iconType) { }
	// RVA: 0x27bc694 VA: 0x7594dd4694
	public Void .ctor() { }
}
```