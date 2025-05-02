# ActMultiV3BattleFinishIllustView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Transform _illustContainer`

- `CharUISkinStruct m_charSkin`

- `UICharacterIllust m_illust`


## Methods

- `Void Render(CharUISkinStruct)`

- `Void PlayVoice(CharWordShowType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3BattleFinishIllustView : MonoBehaviour, IHotfixable
{
	private Transform _illustContainer; // 0x18
	private CharUISkinStruct m_charSkin; // 0x20
	private UICharacterIllust m_illust; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_PlayVoice; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x30e2334 VA: 0x75956fa334
	public Void Render(CharUISkinStruct secretaryCharSkin) { }
	// RVA: 0x30e2460 VA: 0x75956fa460
	public Void PlayVoice(CharWordShowType charWordShowType) { }
	// RVA: 0x30e25f0 VA: 0x75956fa5f0
	public Void .ctor() { }
}
```