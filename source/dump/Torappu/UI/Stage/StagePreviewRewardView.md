# StagePreviewRewardView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `StageRewardDetailPluginHandler m_pluginHandler`


## Methods

- `Void Init(List`1, List`1, Boolean, Boolean)`

- `Void Init(Config)`

- `Boolean _CheckGroupViewAvail(List`1, List`1)`

- `Void _Init(StageRewardDetailPluginHandler, List`1, List`1, Boolean, Boolean)`

- `IEnumerator _UpdateLayoutCoroutine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StagePreviewRewardView : MonoBehaviour
{
	private List`1 _groupViewList; // 0x18
	private StageRewardDetailPluginHandler m_pluginHandler; // 0x20


	// RVA: 0x2f9f264 VA: 0x75955b7264
	public Void Init(List`1 viewModelList, List`1 timelyReward, Boolean getFlag, Boolean completeFlag) { }
	// RVA: 0x2f9f5c8 VA: 0x75955b75c8
	public Void Init(Config config) { }
	// RVA: 0x2f9f788 VA: 0x75955b7788
	private Boolean _CheckGroupViewAvail(List`1 dropTypeHide, List`1 dropTypeList) { }
	// RVA: 0x2f9f8e8 VA: 0x75955b78e8
	private Void _Init(StageRewardDetailPluginHandler pluginHandler, List`1 viewModelList, List`1 timelyReward, Boolean getFlag, Boolean completeFlag) { }
	// RVA: 0x2f9f874 VA: 0x75955b7874
	private IEnumerator _UpdateLayoutCoroutine() { }
	// RVA: 0x2f9f9e8 VA: 0x75955b79e8
	public Void .ctor() { }
}
```