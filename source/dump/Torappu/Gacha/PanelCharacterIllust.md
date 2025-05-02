# PanelCharacterIllust

**Namespace:** `Torappu.Gacha`


## Fields

- `UICharacterIllust m_illust`


## Properties

- `Texture mainTexture`


## Methods

- `Texture get_mainTexture()`

- `Void SetData(CharacterConfig)`

- `Void Reset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Gacha
public class PanelCharacterIllust : MonoBehaviour, IHotfixable
{
	private UICharacterIllust m_illust; // 0x18
	private static DelegateBridge __Hotfix0_get_mainTexture; // 0x0
	private static DelegateBridge __Hotfix0_SetData; // 0x8
	private static DelegateBridge __Hotfix0_Reset; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Texture mainTexture { get; }

	// RVA: 0x35cb258 VA: 0x7595be3258
	public Texture get_mainTexture() { }
	// RVA: 0x35cb320 VA: 0x7595be3320
	public Void SetData(CharacterConfig config) { }
	// RVA: 0x35cb438 VA: 0x7595be3438
	public Void Reset() { }
	// RVA: 0x35cb528 VA: 0x7595be3528
	public Void .ctor() { }
}
```