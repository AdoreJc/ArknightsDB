# UIBattleSandboxResItem

**Namespace:** `Torappu.Battle.UI.Sandbox`


## Fields

- `UIAtlasImage _resTypeIcon`

- `UIAtlasImage _resRarityBack`

- `Text _resAmountText`

- `UIAtlasObject _battleAtlas`

- `SandboxGameMode m_gameMode`


## Methods

- `Void OnInit(ResPackType)`

- `Void UpdateAmount(Int32, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Sandbox
public class UIBattleSandboxResItem : MonoBehaviour, IHotfixable
{
	private UIAtlasImage _resTypeIcon; // 0x18
	private UIAtlasImage _resRarityBack; // 0x20
	private Text _resAmountText; // 0x28
	private UIAtlasObject _battleAtlas; // 0x30
	private String[] _resRarityName; // 0x38
	private SandboxGameMode m_gameMode; // 0x40
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_UpdateAmount; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x20c2df4 VA: 0x75946dadf4
	public Void OnInit(ResPackType resType) { }
	// RVA: 0x20c306c VA: 0x75946db06c
	public Void UpdateAmount(Int32 resAmount, Boolean forceActive) { }
	// RVA: 0x20c31c4 VA: 0x75946db1c4
	public Void .ctor() { }
}
```