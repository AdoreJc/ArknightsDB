# CampaignLadderItemView

**Namespace:** `Torappu.UI.Stage.Campaign`


## Fields

- `SimpleLayoutContent _content`

- `LadderItem m_ladderItem`

- `Boolean m_hasInited`

- `Adapter m_adapter`


## Methods

- `Void RenderView(LadderItem)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.Campaign
public class CampaignLadderItemView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _content; // 0x18
	private LadderItem m_ladderItem; // 0x20
	private Boolean m_hasInited; // 0x28
	private Adapter m_adapter; // 0x30
	private static DelegateBridge __Hotfix0_RenderView; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2fe1a2c VA: 0x75955f9a2c
	public Void RenderView(LadderItem ladderItemData) { }
	// RVA: 0x2fe1ad0 VA: 0x75955f9ad0
	private Void _InitIfNot() { }
	// RVA: 0x2fe1c34 VA: 0x75955f9c34
	public Void .ctor() { }
}
```