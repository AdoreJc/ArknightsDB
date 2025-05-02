# YostarSettingViewOthers

**Namespace:** `YostarSDK.UI`


## Fields

- `Text _textDiamondDetail`

- `Text _textContactCustomerService`

- `Text _textBtnDmndDetail`

- `Text _textBtnCCS`

- `YostarSDK m_sdk`


## Methods

- `Void Render(YostarSDK)`

- `Void _RenderConstTexts()`

- `Void EventOnDiamondInfoClicked()`

- `Void EventOnCCSClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : YostarSDK.UI
public class YostarSettingViewOthers : MonoBehaviour, IHotfixable
{
	private Text _textDiamondDetail; // 0x18
	private Text _textContactCustomerService; // 0x20
	private Text _textBtnDmndDetail; // 0x28
	private Text _textBtnCCS; // 0x30
	private YostarSDK m_sdk; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__RenderConstTexts; // 0x8
	private static DelegateBridge __Hotfix0_EventOnDiamondInfoClicked; // 0x10
	private static DelegateBridge __Hotfix0_EventOnCCSClicked; // 0x18
	private static DelegateBridge __Hotfix0__FormatRegisterTime; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x257e0f8 VA: 0x7594b960f8
	public Void Render(YostarSDK sdk) { }
	// RVA: 0x257e184 VA: 0x7594b96184
	private Void _RenderConstTexts() { }
	// RVA: 0x257e284 VA: 0x7594b96284
	public Void EventOnDiamondInfoClicked() { }
	// RVA: 0x257e328 VA: 0x7594b96328
	public Void EventOnCCSClicked() { }
	// RVA: 0x257e4b0 VA: 0x7594b964b0
	private static String _FormatRegisterTime(Int64 ts) { }
	// RVA: 0x257e804 VA: 0x7594b96804
	public Void .ctor() { }
}
```