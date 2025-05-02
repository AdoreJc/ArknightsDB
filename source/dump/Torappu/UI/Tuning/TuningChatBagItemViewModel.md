# TuningChatBagItemViewModel

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `TuningCommonCardModel cardModel`

- `String productId`

- `Boolean isHidden`

- `String titleDesc`

- `String formColor`

- `String formDesc`

- `String orcheDesc`

- `String hiddenDesc`

- `String musicMainId`

- `String musicSubId`


## Methods

- `Void LoadData(String, String, TuningCommonCardModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningChatBagItemViewModel : IHotfixable
{
	public TuningCommonCardModel cardModel; // 0x10
	public String productId; // 0x18
	public Boolean isHidden; // 0x20
	public String titleDesc; // 0x28
	public String formColor; // 0x30
	public String formDesc; // 0x38
	public String orcheDesc; // 0x40
	public String hiddenDesc; // 0x48
	public String musicMainId; // 0x50
	public String musicSubId; // 0x58
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2320cc0 VA: 0x7594938cc0
	public Void LoadData(String actId, String product, TuningCommonCardModel model) { }
	// RVA: 0x23210f0 VA: 0x75949390f0
	public Void .ctor() { }
}
```