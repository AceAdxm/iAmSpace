<h1 align="center">
	Cherax Lua Doc (but horrible)
</h1>

<details>
	<summary>
		CBaseModelInfo
	</summary>
	<details style="margin-left:16px;">
		<summary>
			FromAddress
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">CBaseModelInfo CBaseModelInfo.FromAddress(int address)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetAddress
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object:GetAddress()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsObject
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsObject()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsPed
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsPed()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsVehicle
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsVehicle()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsWorldObject
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsWorldObject()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Model
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.Model
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ModelIndex
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.ModelIndex
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CDoorCreationDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			DoorModel
		</summary>
		<div style="margin-left:16px;">
			<p>0xC0</p>
			<pre><code class="language-lua">int object.DoorModel
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CDynamicEntityGameStateDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			InteriorProxyLoc
		</summary>
		<div style="margin-left:16px;">
			<p>0x00C0</p>
			<pre><code class="language-lua">int object.InteriorProxyLoc
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			decoratorListCount
		</summary>
		<div style="margin-left:16px;">
			<p>0x00C8</p>
			<pre><code class="language-lua">int object.decoratorListCount
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			loadsCollisions
		</summary>
		<div style="margin-left:16px;">
			<p>0x00C4</p>
			<pre><code class="language-lua">bool object.loadsCollisions
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			retained
		</summary>
		<div style="margin-left:16px;">
			<p>0x00C5</p>
			<pre><code class="language-lua">bool object.retained
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CEntity
	</summary>
	<details style="margin-left:16px;">
		<summary>
			FromAddress
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">CEntity CEntity.FromAddress(int address)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetAddress
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object:GetAddress()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetAttachmentExtension
		</summary>
		<div style="margin-left:16px;">
			<p>Check if the extension is not nil before using it.</p>
			<pre><code class="language-lua">fwAttachmentEntityExtension object:GetAttachmentExtension()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetType
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">eEntityType object:GetType()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetVelocity
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the current velocity vector in meters per second.</p>
			<pre><code class="language-lua">V3 object:GetVelocity()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HeightMultiplier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.HeightMultiplier
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsDynamic
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsDynamic
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsFixed
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsFixed
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsFixedByNetwork
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsFixedByNetwork
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsObject
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsObject()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsPed
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsPed()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsPhysical
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsPhysical()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsVehicle
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsVehicle()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsVisible
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsVisible
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ModelInfo
		</summary>
		<div style="margin-left:16px;">
			<p>Check if 'object.ModelInfo' is not nil before using it.</p>
			<pre><code class="language-lua">CBaseModelInfo object.ModelInfo
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Position
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">V3 object.Position
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ThicknessMultiplier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.ThicknessMultiplier
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			WidthMultiplier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.WidthMultiplier
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CEntityScriptGameStateDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			disableCollisionCompletely
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.disableCollisionCompletely
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isFixed
		</summary>
		<div style="margin-left:16px;">
			<p>gamestate flag indicating whether the object is using fixed physics</p>
			<pre><code class="language-lua">bool object.isFixed
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			usesCollision
		</summary>
		<div style="margin-left:16px;">
			<p>gamestate flag indicating whether the object is using collision</p>
			<pre><code class="language-lua">bool object.usesCollision
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CHeliControlDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			BVTHControlVertVel
		</summary>
		<div style="margin-left:16px;">
			<p>CTaskBringVehicleToHalt bControlVerticalVelocity</p>
			<pre><code class="language-lua">bool object.BVTHControlVertVel
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BVTHStoppingDist
		</summary>
		<div style="margin-left:16px;">
			<p>CTaskBringVehicleToHalt stopping dist</p>
			<pre><code class="language-lua">number object.BVTHStoppingDist
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HasTargetGravityScale
		</summary>
		<div style="margin-left:16px;">
			<p>For hover vehicles</p>
			<pre><code class="language-lua">bool object.HasTargetGravityScale
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HasTopSpeedPercentage
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.HasTopSpeedPercentage
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			StickY
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.StickY
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SubCarDive
		</summary>
		<div style="margin-left:16px;">
			<p>the current value of the dive control for sub cars</p>
			<pre><code class="language-lua">number object.SubCarDive
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SubCarPitch
		</summary>
		<div style="margin-left:16px;">
			<p>the current value of the pitch control for sub cars</p>
			<pre><code class="language-lua">number object.SubCarPitch
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TargetGravityScale
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.TargetGravityScale
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bAllLowriderHydraulicsRaised
		</summary>
		<div style="margin-left:16px;">
			<p>CTaskVehiclePlayerDriveAutomobile::ProcessDriverInputsForPlayerOnUpdate; player has raised all lowrider suspension</p>
			<pre><code class="language-lua">bool object.bAllLowriderHydraulicsRaised
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bHasLandingGear
		</summary>
		<div style="margin-left:16px;">
			<p>if the helicopter has landing gear</p>
			<pre><code class="language-lua">bool object.bHasLandingGear
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bIsClosingAnyDoor
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bIsClosingAnyDoor
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bIsNitrousOverrideActive
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bIsNitrousOverrideActive
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bModifiedLowriderSuspension
		</summary>
		<div style="margin-left:16px;">
			<p>CTaskVehiclePlayerDriveAutomobile::ProcessDriverInputsForPlayerOnUpdate; player has modified suspension of lowrider</p>
			<pre><code class="language-lua">bool object.bModifiedLowriderSuspension
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bNitrousActive
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bNitrousActive
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bPlayHydraulicsActivationSound
		</summary>
		<div style="margin-left:16px;">
			<p>Hydraulics sound effect when activated</p>
			<pre><code class="language-lua">bool object.bPlayHydraulicsActivationSound
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bPlayHydraulicsBounceSound
		</summary>
		<div style="margin-left:16px;">
			<p>Hydraulics sound effect when bouncing</p>
			<pre><code class="language-lua">bool object.bPlayHydraulicsBounceSound
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bPlayHydraulicsDeactivationSound
		</summary>
		<div style="margin-left:16px;">
			<p>Hydraulics sound effect when de-activated</p>
			<pre><code class="language-lua">bool object.bPlayHydraulicsDeactivationSound
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			brakePedal
		</summary>
		<div style="margin-left:16px;">
			<p>the current value of the brake pedal</p>
			<pre><code class="language-lua">number object.brakePedal
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bringVehicleToHalt
		</summary>
		<div style="margin-left:16px;">
			<p>CTaskBringVehicleToHalt is running as a secondary task</p>
			<pre><code class="language-lua">bool object.bringVehicleToHalt
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			fLowriderSuspension
		</summary>
		<div style="margin-left:16px;">
			<p>Syncs modified lowrider suspension values</p>
			<pre><code class="language-lua">table<int, number> object.fLowriderSuspension
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			hasActiveAITask
		</summary>
		<div style="margin-left:16px;">
			<p>should the heli be fixed if no collision around it?</p>
			<pre><code class="language-lua">bool object.hasActiveAITask
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			hasJetpackStrafeForceScale
		</summary>
		<div style="margin-left:16px;">
			<p>does the heli have the jetpack effect</p>
			<pre><code class="language-lua">bool object.hasJetpackStrafeForceScale
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isInBurnout
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.isInBurnout
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isSubCar
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.isSubCar
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			jetPackStrafeForceScale
		</summary>
		<div style="margin-left:16px;">
			<p>force of jetpack strafe</p>
			<pre><code class="language-lua">number object.jetPackStrafeForceScale
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			jetPackThrusterThrottle
		</summary>
		<div style="margin-left:16px;">
			<p>force of jetpack thrusters</p>
			<pre><code class="language-lua">number object.jetPackThrusterThrottle
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			kersActive
		</summary>
		<div style="margin-left:16px;">
			<p>indicates if the kers system is active</p>
			<pre><code class="language-lua">bool object.kersActive
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			landingGearState
		</summary>
		<div style="margin-left:16px;">
			<p>landing gear state - if the helicopter has landing gear</p>
			<pre><code class="language-lua">int object.landingGearState
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			lockedToXY
		</summary>
		<div style="margin-left:16px;">
			<p>anchor state for anchorable sea helis</p>
			<pre><code class="language-lua">bool object.lockedToXY
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			mainRotorStopped
		</summary>
		<div style="margin-left:16px;">
			<p>is the main rotor stopped?</p>
			<pre><code class="language-lua">bool object.mainRotorStopped
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			numWheels
		</summary>
		<div style="margin-left:16px;">
			<p>number of wheels on this car</p>
			<pre><code class="language-lua">int object.numWheels
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			pitchControl
		</summary>
		<div style="margin-left:16px;">
			<p>pitch control of the helicopter</p>
			<pre><code class="language-lua">number object.pitchControl
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			reducedSuspensionForce
		</summary>
		<div style="margin-left:16px;">
			<p>reduced suspension force used to "stance" tuner pack vehicles</p>
			<pre><code class="language-lua">bool object.reducedSuspensionForce
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			roadNodeAddress
		</summary>
		<div style="margin-left:16px;">
			<p>the current road node the vehicle is driving from</p>
			<pre><code class="language-lua">int object.roadNodeAddress
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			rollControl
		</summary>
		<div style="margin-left:16px;">
			<p>roll control of the helicopter</p>
			<pre><code class="language-lua">number object.rollControl
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			subCarYaw
		</summary>
		<div style="margin-left:16px;">
			<p>the current value of the yaw control for sub cars</p>
			<pre><code class="language-lua">number object.subCarYaw
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			throttle
		</summary>
		<div style="margin-left:16px;">
			<p>the current value of the throttle</p>
			<pre><code class="language-lua">number object.throttle
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			throttleControl
		</summary>
		<div style="margin-left:16px;">
			<p>throttle control of the helicopter</p>
			<pre><code class="language-lua">number object.throttleControl
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			topSpeedPercent
		</summary>
		<div style="margin-left:16px;">
			<p>set to the maximum speed a vehicle can travel at</p>
			<pre><code class="language-lua">number object.topSpeedPercent
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			yawControl
		</summary>
		<div style="margin-left:16px;">
			<p>yaw control of the helicopter</p>
			<pre><code class="language-lua">number object.yawControl
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CNetGamePlayer
	</summary>
	<details style="margin-left:16px;">
		<summary>
			CxnId
		</summary>
		<div style="margin-left:16px;">
			<p>Connection Id</p>
			<pre><code class="language-lua">int object.CxnId
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetGamerInfo
		</summary>
		<div style="margin-left:16px;">
			<p>Returns a structure 'GamerInfo' holding information about the player.</p>
			<pre><code class="language-lua">GamerInfo object:GetGamerInfo()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetName
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">string object:GetName()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsLocalPlayer
		</summary>
		<div style="margin-left:16px;">
			<p>Check whether its the local player or not.</p>
			<pre><code class="language-lua">bool object:IsLocalPlayer()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsReportBitSet
		</summary>
		<div style="margin-left:16px;">
			<p>Check if a report flag is set. Also called Rockstar Anti Cheat(RAC).</p>
			<pre><code class="language-lua">bool object:isReportBitSet(eReportReason reason)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PlayerId
		</summary>
		<div style="margin-left:16px;">
			<p>Player Id</p>
			<pre><code class="language-lua">int object.PlayerId
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PlayerInfo
		</summary>
		<div style="margin-left:16px;">
			<p>Returns a class 'CPlayerInfo' holding information about the player.</p>
			<pre><code class="language-lua">CPlayerInfo object.PlayerInfo
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CNetObject
	</summary>
	<details style="margin-left:16px;">
		<summary>
			GetEntity
		</summary>
		<div style="margin-left:16px;">
			<p>Check if 'object.Entity' is not nil before using it. Invalid for NetObjDoor.</p>
			<pre><code class="language-lua">CPhysical object.Entity
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsRemote
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsRemote
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ObjectID
		</summary>
		<div style="margin-left:16px;">
			<p>Used to identify or to find a netobject.</p>
			<pre><code class="language-lua">int object.ObjectID
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ObjectType
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.ObjectType
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PendingPlayerId
		</summary>
		<div style="margin-left:16px;">
			<p>The next owner of the CNetObject.</p>
			<pre><code class="language-lua">int object.PendingPlayerId
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PlayerId
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.PlayerId
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CObject
	</summary>
	<details style="margin-left:16px;">
		<summary>
			DisableInvincible
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void object:DisableInvincible()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			EnableInvincible
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void object:EnableInvincible()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			FromAddress
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">CObject CObject.FromAddress(int address)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetAddress
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object:GetAddress()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetAttachmentExtension
		</summary>
		<div style="margin-left:16px;">
			<p>Check if the extension is not nil before using it.</p>
			<pre><code class="language-lua">fwAttachmentEntityExtension object:GetAttachmentExtension()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetType
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">eEntityType object:GetType()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetVelocity
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the current velocity vector in meters per second.</p>
			<pre><code class="language-lua">V3 object:GetVelocity()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HeightMultiplier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.HeightMultiplier
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsDynamic
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsDynamic
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsFixed
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsFixed
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsFixedByNetwork
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsFixedByNetwork
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsInWater
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsInWater
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsInvincible
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsInvincible()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsNotBuoyant
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsNotBuoyant
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsObject
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsObject()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsPed
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsPed()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsPhysical
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsPhysical()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsRenderScorched
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsRenderScorched
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsVehicle
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsVehicle()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsVisible
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsVisible
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ModelInfo
		</summary>
		<div style="margin-left:16px;">
			<p>Check if 'object.ModelInfo' is not nil before using it.</p>
			<pre><code class="language-lua">CBaseModelInfo object.ModelInfo
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NetObject
		</summary>
		<div style="margin-left:16px;">
			<p>Check if 'object.NetObject' is not nil before using it.</p>
			<pre><code class="language-lua">CNetObject object.NetObject
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Position
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">V3 object.Position
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ThicknessMultiplier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.ThicknessMultiplier
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			WidthMultiplier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.WidthMultiplier
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CObjectCreationDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			CanBlendWhenFixed
		</summary>
		<div style="margin-left:16px;">
			<p>indicates the network blender can run when the object is using fixed physics</p>
			<pre><code class="language-lua">bool object.CanBlendWhenFixed
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DestroyFrags
		</summary>
		<div style="margin-left:16px;">
			<p>if the object is breakable, destroy any frags created by the breaking</p>
			<pre><code class="language-lua">bool object.DestroyFrags
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HasExploded
		</summary>
		<div style="margin-left:16px;">
			<p>the object has exploded</p>
			<pre><code class="language-lua">bool object.HasExploded
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsAmbientFence
		</summary>
		<div style="margin-left:16px;">
			<p>the object is an uprooted fence</p>
			<pre><code class="language-lua">bool object.IsAmbientFence
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsBroken
		</summary>
		<div style="margin-left:16px;">
			<p>the object is broken / damaged</p>
			<pre><code class="language-lua">bool object.IsBroken
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsFragObject
		</summary>
		<div style="margin-left:16px;">
			<p>this object is a frag object</p>
			<pre><code class="language-lua">bool object.IsFragObject
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			KeepRegistered
		</summary>
		<div style="margin-left:16px;">
			<p>the object must remain registered</p>
			<pre><code class="language-lua">bool object.KeepRegistered
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ScriptGrabPosition
		</summary>
		<div style="margin-left:16px;">
			<p>world position script grabbed this object from</p>
			<pre><code class="language-lua">V3 object.ScriptGrabPosition
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ScriptGrabRadius
		</summary>
		<div style="margin-left:16px;">
			<p>radius used by script to grab this object</p>
			<pre><code class="language-lua">number object.ScriptGrabRadius
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ScriptGrabbedFromWorld
		</summary>
		<div style="margin-left:16px;">
			<p>has script grabbed this object from a world position?</p>
			<pre><code class="language-lua">bool object.ScriptGrabbedFromWorld
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			dummyPosition
		</summary>
		<div style="margin-left:16px;">
			<p>position of the dummy object this object was instanced from</p>
			<pre><code class="language-lua">V3 object.dummyPosition
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			fragGroupIndex
		</summary>
		<div style="margin-left:16px;">
			<p>the frag group index (used by fragment cache objects)</p>
			<pre><code class="language-lua">int object.fragGroupIndex
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			fragParentVehicle
		</summary>
		<div style="margin-left:16px;">
			<p>if set, this object is a vehicle fragment and it belongs to this vehicle id</p>
			<pre><code class="language-lua">int object.fragParentVehicle
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			hasGameObject
		</summary>
		<div style="margin-left:16px;">
			<p>is there a prop object associated with this network object?</p>
			<pre><code class="language-lua">bool object.hasGameObject
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			hasInitPhysics
		</summary>
		<div style="margin-left:16px;">
			<p>has this object initialized physics?</p>
			<pre><code class="language-lua">bool object.hasInitPhysics
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			lodDistance
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.lodDistance
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			lodOrphanHd
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.lodOrphanHd
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			modelHash
		</summary>
		<div style="margin-left:16px;">
			<p>model index</p>
			<pre><code class="language-lua">int object.modelHash
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			noReassign
		</summary>
		<div style="margin-left:16px;">
			<p>stop the object changing owner</p>
			<pre><code class="language-lua">bool object.noReassign
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			objectMatrix
		</summary>
		<div style="margin-left:16px;">
			<p>the position of the object (used when the network object has no game object)</p>
			<pre><code class="language-lua">table<int, V3> object.objectMatrix
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			objectPosition
		</summary>
		<div style="margin-left:16px;">
			<p>position of the object (used when there is no game object)</p>
			<pre><code class="language-lua">V3 object.objectPosition
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ownedBy
		</summary>
		<div style="margin-left:16px;">
			<p>created by</p>
			<pre><code class="language-lua">int object.ownedBy
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ownershipToken
		</summary>
		<div style="margin-left:16px;">
			<p>used when there is no associated prop (and sync data) for this network object</p>
			<pre><code class="language-lua">int object.ownershipToken
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			playerWantsControl
		</summary>
		<div style="margin-left:16px;">
			<p>does the creating player want control of this object</p>
			<pre><code class="language-lua">bool object.playerWantsControl
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CObjectGameStateDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			HasBeenPickedUpByHook
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.HasBeenPickedUpByHook
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			brokenFlags
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.brokenFlags
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			hasAddedPhysics
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.hasAddedPhysics
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			objectHasExploded
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.objectHasExploded
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			popTires
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.popTires
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			taskDataSize
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.taskDataSize
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			taskSpecificData
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">table<int, int> object.taskSpecificData
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			taskType
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.taskType
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			visible
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.visible
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CObjectSectorPosNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			SectorPosX
		</summary>
		<div style="margin-left:16px;">
			<p>X position of this object within the current sector</p>
			<pre><code class="language-lua">number object.SectorPosX
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SectorPosY
		</summary>
		<div style="margin-left:16px;">
			<p>Y position of this object within the current sector</p>
			<pre><code class="language-lua">number object.SectorPosY
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SectorPosZ
		</summary>
		<div style="margin-left:16px;">
			<p>Z position of this object within the current sector</p>
			<pre><code class="language-lua">number object.SectorPosZ
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			UseHighPrecision
		</summary>
		<div style="margin-left:16px;">
			<p>Indicates whether the position should be synced with high precision</p>
			<pre><code class="language-lua">bool object.UseHighPrecision
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CPed
	</summary>
	<details style="margin-left:16px;">
		<summary>
			Armor
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.Armor
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CurVehicle
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">CVehicle object.CurVehicle
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DisableInvincible
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void object:DisableInvincible()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			EnableInvincible
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void object:EnableInvincible()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			FromAddress
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">CPed CPed.FromAddress(int address)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetAddress
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object:GetAddress()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetAttachmentExtension
		</summary>
		<div style="margin-left:16px;">
			<p>Check if the extension is not nil before using it.</p>
			<pre><code class="language-lua">fwAttachmentEntityExtension object:GetAttachmentExtension()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetType
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">eEntityType object:GetType()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetVelocity
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the current velocity vector in meters per second.</p>
			<pre><code class="language-lua">V3 object:GetVelocity()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Health
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.Health
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HeightMultiplier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.HeightMultiplier
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsDynamic
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsDynamic
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsFixed
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsFixed
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsFixedByNetwork
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsFixedByNetwork
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsInVehicle
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsInVehicle()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsInWater
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsInWater
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsInvincible
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsInvincible()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsNotBuoyant
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsNotBuoyant
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsObject
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsObject()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsPed
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsPed()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsPhysical
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsPhysical()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsPlayer
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsPlayer()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsRenderScorched
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsRenderScorched
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsVehicle
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsVehicle()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsVisible
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsVisible
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LastVehicle
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">CVehicle object.LastVehicle
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			MaxHealth
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.MaxHealth
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ModelInfo
		</summary>
		<div style="margin-left:16px;">
			<p>Check if 'object.ModelInfo' is not nil before using it.</p>
			<pre><code class="language-lua">CBaseModelInfo object.ModelInfo
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NetObject
		</summary>
		<div style="margin-left:16px;">
			<p>Check if 'object.NetObject' is not nil before using it.</p>
			<pre><code class="language-lua">CNetObject object.NetObject
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PlayerInfo
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">CPlayerInfo object.PlayerInfo
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Position
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">V3 object.Position
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ThicknessMultiplier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.ThicknessMultiplier
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			WidthMultiplier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.WidthMultiplier
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CPedAppearanceDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			PhoneMode
		</summary>
		<div style="margin-left:16px;">
			<p>for secondary task phone</p>
			<pre><code class="language-lua">int object.PhoneMode
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			facialClipSetId
		</summary>
		<div style="margin-left:16px;">
			<p>the facial clipset used by the ped</p>
			<pre><code class="language-lua">int object.facialClipSetId
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			facialIdleAnimOverrideClipDictNameHash
		</summary>
		<div style="margin-left:16px;">
			<p>the dictionary used by the ped</p>
			<pre><code class="language-lua">int object.facialIdleAnimOverrideClipDictNameHash
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			facialIdleAnimOverrideClipNameHash
		</summary>
		<div style="margin-left:16px;">
			<p>the facial clip used by the ped</p>
			<pre><code class="language-lua">int object.facialIdleAnimOverrideClipNameHash
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			helmetProp
		</summary>
		<div style="margin-left:16px;">
			<p>what helmet type are we using?</p>
			<pre><code class="language-lua">int object.helmetProp
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			helmetTextureId
		</summary>
		<div style="margin-left:16px;">
			<p>what texture are we going to use for the helmet?</p>
			<pre><code class="language-lua">int object.helmetTextureId
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isAttachingHelmet
		</summary>
		<div style="margin-left:16px;">
			<p>are we attaching a helmet?</p>
			<pre><code class="language-lua">bool object.isAttachingHelmet
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isRemovingHelmet
		</summary>
		<div style="margin-left:16px;">
			<p>are we removing a helmet?</p>
			<pre><code class="language-lua">bool object.isRemovingHelmet
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isVisorSwitching
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.isVisorSwitching
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isWearingHelmet
		</summary>
		<div style="margin-left:16px;">
			<p>are we wearing a helmet?</p>
			<pre><code class="language-lua">bool object.isWearingHelmet
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			parachutePackTintIndex
		</summary>
		<div style="margin-left:16px;">
			<p>what colour the parachute pack will appear on deployment...</p>
			<pre><code class="language-lua">int object.parachutePackTintIndex
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			parachuteTintIndex
		</summary>
		<div style="margin-left:16px;">
			<p>what colour the parachute will appear on deployment...</p>
			<pre><code class="language-lua">int object.parachuteTintIndex
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			supportsVisor
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.supportsVisor
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			targetVisorState
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.targetVisorState
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			visorDownProp
		</summary>
		<div style="margin-left:16px;">
			<p>what helmet type are we using?</p>
			<pre><code class="language-lua">int object.visorDownProp
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			visorIsUp
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.visorIsUp
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			visorUpProp
		</summary>
		<div style="margin-left:16px;">
			<p>what helmet type are we using?</p>
			<pre><code class="language-lua">int object.visorUpProp
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CPedAttachDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			attachBone
		</summary>
		<div style="margin-left:16px;">
			<p>bone ped is attached to</p>
			<pre><code class="language-lua">int object.attachBone
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			attachFlags
		</summary>
		<div style="margin-left:16px;">
			<p>attachment flags</p>
			<pre><code class="language-lua">int object.attachFlags
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			attachHeading
		</summary>
		<div style="margin-left:16px;">
			<p>attachment heading</p>
			<pre><code class="language-lua">number object.attachHeading
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			attachHeadingLimit
		</summary>
		<div style="margin-left:16px;">
			<p>attachment heading limit</p>
			<pre><code class="language-lua">number object.attachHeadingLimit
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			attachOffset
		</summary>
		<div style="margin-left:16px;">
			<p>offset from attachment position</p>
			<pre><code class="language-lua">V3 object.attachOffset
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			attachQuat
		</summary>
		<div style="margin-left:16px;">
			<p>attachment quaternion</p>
			<pre><code class="language-lua">V3 object.attachQuat
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			attached
		</summary>
		<div style="margin-left:16px;">
			<p>is the ped attached?</p>
			<pre><code class="language-lua">bool object.attached
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			attachedObjectID
		</summary>
		<div style="margin-left:16px;">
			<p>ID of Object ped is attached to</p>
			<pre><code class="language-lua">int object.attachedObjectID
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			attachedToGround
		</summary>
		<div style="margin-left:16px;">
			<p>whether the ped is attached to ground or not</p>
			<pre><code class="language-lua">bool object.attachedToGround
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CPedCreationDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			IsRespawnObjId
		</summary>
		<div style="margin-left:16px;">
			<p>is a valid respawn object id</p>
			<pre><code class="language-lua">bool object.IsRespawnObjId
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RespawnFlaggedForRemoval
		</summary>
		<div style="margin-left:16px;">
			<p>True if the respawn ped was flagged for removal</p>
			<pre><code class="language-lua">bool object.RespawnFlaggedForRemoval
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			attDamageToPlayer
		</summary>
		<div style="margin-left:16px;">
			<p>ID of the Player to attribute damage to.</p>
			<pre><code class="language-lua">int object.attDamageToPlayer
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			hasAttDamageToPlayer
		</summary>
		<div style="margin-left:16px;">
			<p>True if the ped damage should be attributed to a certain player.</p>
			<pre><code class="language-lua">bool object.hasAttDamageToPlayer
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			hasProp
		</summary>
		<div style="margin-left:16px;">
			<p>does this ped carry a prop</p>
			<pre><code class="language-lua">bool object.hasProp
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			inVehicle
		</summary>
		<div style="margin-left:16px;">
			<p>is this ped in a vehicle?</p>
			<pre><code class="language-lua">bool object.inVehicle
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isStanding
		</summary>
		<div style="margin-left:16px;">
			<p>is this ped standing?</p>
			<pre><code class="language-lua">bool object.isStanding
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			maxHealth
		</summary>
		<div style="margin-left:16px;">
			<p>max health as it can be altered</p>
			<pre><code class="language-lua">int object.maxHealth
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			modelHash
		</summary>
		<div style="margin-left:16px;">
			<p>model index</p>
			<pre><code class="language-lua">int object.modelHash
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			popType
		</summary>
		<div style="margin-left:16px;">
			<p>population type</p>
			<pre><code class="language-lua">int object.popType
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			propHash
		</summary>
		<div style="margin-left:16px;">
			<p>index of the prop the ped is carrying</p>
			<pre><code class="language-lua">int object.propHash
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			randomSeed
		</summary>
		<div style="margin-left:16px;">
			<p>random seed</p>
			<pre><code class="language-lua">int object.randomSeed
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			seat
		</summary>
		<div style="margin-left:16px;">
			<p>seat the ped is sitting in in the vehicle</p>
			<pre><code class="language-lua">int object.seat
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			vehicleID
		</summary>
		<div style="margin-left:16px;">
			<p>ID of the vehicle this ped is currently in</p>
			<pre><code class="language-lua">int object.vehicleID
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			voiceHash
		</summary>
		<div style="margin-left:16px;">
			<p>voice hash code</p>
			<pre><code class="language-lua">int object.voiceHash
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			wearingAHelmet
		</summary>
		<div style="margin-left:16px;">
			<p>is the ped wearing a helmet *put on via CPedHelmetComponent*</p>
			<pre><code class="language-lua">bool object.wearingAHelmet
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CPedGameStateDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			HasValidWeaponClipset
		</summary>
		<div style="margin-left:16px;">
			<p>do we have a valid weapon clip set? Used as part of a hack fix for when pointing while holding a weapon</p>
			<pre><code class="language-lua">bool object.HasValidWeaponClipset
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LookAtFlags
		</summary>
		<div style="margin-left:16px;">
			<p>eHeadIkFlags</p>
			<pre><code class="language-lua">int object.LookAtFlags
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LookAtObjectID
		</summary>
		<div style="margin-left:16px;">
			<p>If looking at an object, ID of object ped is looking at</p>
			<pre><code class="language-lua">int object.LookAtObjectID
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			arrestState
		</summary>
		<div style="margin-left:16px;">
			<p>ped arrest state</p>
			<pre><code class="language-lua">int object.arrestState
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bActionModeEnabled
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bActionModeEnabled
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bDisableStartEngine
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bDisableStartEngine
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bPedPerceptionModified
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bPedPerceptionModified
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bStealthModeEnabled
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bStealthModeEnabled
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bvehicleweaponindex
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bvehicleweaponindex
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			canBeIncapacitated
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.canBeIncapacitated
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			changeToAmbientPopTypeOnMigration
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.changeToAmbientPopTypeOnMigration
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			cleardamagecount
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.cleardamagecount
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			createdByConcealedPlayer
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.createdByConcealedPlayer
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			custodianID
		</summary>
		<div style="margin-left:16px;">
			<p>ID of the player that is and has taken us into custody.</p>
			<pre><code class="language-lua">int object.custodianID
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			deathState
		</summary>
		<div style="margin-left:16px;">
			<p>ped death state</p>
			<pre><code class="language-lua">int object.deathState
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			disableBlindFiringInShotReactions
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.disableBlindFiringInShotReactions
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			doingWeaponSwap
		</summary>
		<div style="margin-left:16px;">
			<p>The ped is running a CTaskSwapWeapon</p>
			<pre><code class="language-lua">bool object.doingWeaponSwap
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			dontActivateRagdollFromAnyPedImpact
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.dontActivateRagdollFromAnyPedImpact
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			dontBehaveLikeLaw
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.dontBehaveLikeLaw
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			equippedGadgets
		</summary>
		<div style="margin-left:16px;">
			<p>hashes of gadgets equipped</p>
			<pre><code class="language-lua">table<int, int> object.equippedGadgets
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			flashLightOn
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.flashLightOn
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			hasCustodianOrArrestFlags
		</summary>
		<div style="margin-left:16px;">
			<p>does this ped have a custodian.</p>
			<pre><code class="language-lua">bool object.hasCustodianOrArrestFlags
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			hasDroppedWeapon
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.hasDroppedWeapon
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			hasVehicle
		</summary>
		<div style="margin-left:16px;">
			<p>does this ped have a vehicle?</p>
			<pre><code class="language-lua">bool object.hasVehicle
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			hitByTranqWeapon
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.hitByTranqWeapon
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			inVehicle
		</summary>
		<div style="margin-left:16px;">
			<p>is this ped in a vehicle?</p>
			<pre><code class="language-lua">bool object.inVehicle
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isDuckingInVehicle
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.isDuckingInVehicle
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isLookingAtObject
		</summary>
		<div style="margin-left:16px;">
			<p>Is looking at an object</p>
			<pre><code class="language-lua">bool object.isLookingAtObject
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isUpright
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.isUpright
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isUsingAlternateLowriderLeanAnims
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.isUsingAlternateLowriderLeanAnims
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isUsingLowriderLeanAnims
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.isUsingLowriderLeanAnims
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			keepTasksAfterCleanup
		</summary>
		<div style="margin-left:16px;">
			<p>ped keeps his tasks given when he was a script ped</p>
			<pre><code class="language-lua">bool object.keepTasksAfterCleanup
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			killedByKnockdown
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.killedByKnockdown
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			killedByStandardMelee
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.killedByStandardMelee
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			killedByStealth
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.killedByStealth
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			killedByTakedown
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.killedByTakedown
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			mountID
		</summary>
		<div style="margin-left:16px;">
			<p>ID of the mount this ped is currently in</p>
			<pre><code class="language-lua">int object.mountID
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			nMovementModeOverrideID
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.nMovementModeOverrideID
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			numGadgets
		</summary>
		<div style="margin-left:16px;">
			<p>the number of currently equipped gadgets</p>
			<pre><code class="language-lua">int object.numGadgets
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			numWeaponComponents
		</summary>
		<div style="margin-left:16px;">
			<p>the number of weapon components on current equipped weapon</p>
			<pre><code class="language-lua">int object.numWeaponComponents
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			onMount
		</summary>
		<div style="margin-left:16px;">
			<p>is this ped on a mount?</p>
			<pre><code class="language-lua">bool object.onMount
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			permanentlyDisablePotentialToBeWalkedIntoResponse
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.permanentlyDisablePotentialToBeWalkedIntoResponse
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			seat
		</summary>
		<div style="margin-left:16px;">
			<p>seat the ped is sitting in in the vehicle</p>
			<pre><code class="language-lua">int object.seat
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			vehicleID
		</summary>
		<div style="margin-left:16px;">
			<p>ID of the vehicle this ped is currently in</p>
			<pre><code class="language-lua">int object.vehicleID
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			vehicleweaponindex
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.vehicleweaponindex
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			weapon
		</summary>
		<div style="margin-left:16px;">
			<p>currently selected weapon type</p>
			<pre><code class="language-lua">int object.weapon
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			weaponComponents
		</summary>
		<div style="margin-left:16px;">
			<p>hashes of weapon components equipped</p>
			<pre><code class="language-lua">table<int, int> object.weaponComponents
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			weaponComponentsTint
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">table<int, int> object.weaponComponentsTint
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			weaponObjectAttachLeft
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.weaponObjectAttachLeft
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			weaponObjectExists
		</summary>
		<div style="margin-left:16px;">
			<p>is there a weapon object</p>
			<pre><code class="language-lua">bool object.weaponObjectExists
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			weaponObjectHasAmmo
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.weaponObjectHasAmmo
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			weaponObjectTintIndex
		</summary>
		<div style="margin-left:16px;">
			<p>weapon object tint index (coloured weapons)</p>
			<pre><code class="language-lua">int object.weaponObjectTintIndex
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			weaponObjectVisible
		</summary>
		<div style="margin-left:16px;">
			<p>is the weapon object visible</p>
			<pre><code class="language-lua">bool object.weaponObjectVisible
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CPedInventoryDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			allAmmoInfinite
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.allAmmoInfinite
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ammoInfinite
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">table<int, bool> object.ammoInfinite
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ammoQuantity
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">table<int, int> object.ammoQuantity
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ammoSlots
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">table<int, int> object.ammoSlots
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			itemSlotNumComponents
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">table<int, int> object.itemSlotNumComponents
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			itemSlotTint
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">table<int, int> object.itemSlotTint
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			itemSlots
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">table<int, int> object.itemSlots
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			numAmmos
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.numAmmos
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			numItems
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.numItems
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CPedMovementDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			DesiredMoveBlendRatioX
		</summary>
		<div style="margin-left:16px;">
			<p>desired move blend ratio in the X axis</p>
			<pre><code class="language-lua">number object.DesiredMoveBlendRatioX
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DesiredMoveBlendRatioY
		</summary>
		<div style="margin-left:16px;">
			<p>desired move blend ratio in the Y axis</p>
			<pre><code class="language-lua">number object.DesiredMoveBlendRatioY
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DesiredPitch
		</summary>
		<div style="margin-left:16px;">
			<p>desired pitch</p>
			<pre><code class="language-lua">number object.DesiredPitch
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HasDesiredMoveBlendRatioX
		</summary>
		<div style="margin-left:16px;">
			<p>indicates whether the move blend ratio for the ped in the X axis is non-zero</p>
			<pre><code class="language-lua">bool object.HasDesiredMoveBlendRatioX
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HasDesiredMoveBlendRatioY
		</summary>
		<div style="margin-left:16px;">
			<p>indicates whether the move blend ratio for the ped in the Y axis is non-zero</p>
			<pre><code class="language-lua">bool object.HasDesiredMoveBlendRatioY
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HasStopped
		</summary>
		<div style="margin-left:16px;">
			<p>indicates the ped has stopped moving (velocity is zero)</p>
			<pre><code class="language-lua">bool object.HasStopped
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			MaxMoveBlendRatio
		</summary>
		<div style="margin-left:16px;">
			<p>script set max move blend ratio</p>
			<pre><code class="language-lua">number object.MaxMoveBlendRatio
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CPedOrientationDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			currentHeading
		</summary>
		<div style="margin-left:16px;">
			<p>ped current heading</p>
			<pre><code class="language-lua">number object.currentHeading
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			desiredHeading
		</summary>
		<div style="margin-left:16px;">
			<p>ped desired heading</p>
			<pre><code class="language-lua">number object.desiredHeading
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CPedScriptCreationDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			StayInCarWhenJacked
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.StayInCarWhenJacked
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CPedScriptGameStateDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			AngledDefensiveAreaV1
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">V3 object.AngledDefensiveAreaV1
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AngledDefensiveAreaV2
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">V3 object.AngledDefensiveAreaV2
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AngledDefensiveAreaWidth
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.AngledDefensiveAreaWidth
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DefensiveAreaCentre
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">V3 object.DefensiveAreaCentre
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DefensiveAreaRadius
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.DefensiveAreaRadius
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DefensiveAreaType
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.DefensiveAreaType
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			FiringPatternHash
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.FiringPatternHash
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HasDefensiveArea
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.HasDefensiveArea
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HasInVehicleContextHash
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.HasInVehicleContextHash
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NavCapabilityFlags
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.NavCapabilityFlags
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SeatIndexToUseInAGroup
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.SeatIndexToUseInAGroup
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			UseCentreAsGotoPos
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.UseCentreAsGotoPos
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ammoToDrop
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.ammoToDrop
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			combatMovement
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.combatMovement
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			fAccuracy
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.fAccuracy
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			fBlindFireChance
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.fBlindFireChance
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			fBurstDurationInCover
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.fBurstDurationInCover
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			fHomingRocketBreakLockAngle
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.fHomingRocketBreakLockAngle
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			fHomingRocketBreakLockAngleClose
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.fHomingRocketBreakLockAngleClose
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			fHomingRocketBreakLockCloseDistance
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.fHomingRocketBreakLockCloseDistance
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			fMaxInformFriendDistance
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.fMaxInformFriendDistance
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			fMaxShootingDistance
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.fMaxShootingDistance
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			fMaxVehicleTurretFiringRange
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.fMaxVehicleTurretFiringRange
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			fStrafeWhenMovingChance
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.fStrafeWhenMovingChance
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			fTimeBetweenAggressiveMovesDuringVehicleChase
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.fTimeBetweenAggressiveMovesDuringVehicleChase
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			fTimeBetweenBurstsInCover
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.fTimeBetweenBurstsInCover
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			fTimeBetweenPeeks
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.fTimeBetweenPeeks
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			fWeaponDamageModifier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.fWeaponDamageModifier
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			fleeBehaviorFlags
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.fleeBehaviorFlags
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			hasPedType
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.hasPedType
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			inVehicleContextHash
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.inVehicleContextHash
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isAmbientSpeechDisabled
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.isAmbientSpeechDisabled
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isPainAudioDisabled
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.isPainAudioDisabled
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isTargettableByTeam
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.isTargettableByTeam
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			minOnGroundTimeForStun
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.minOnGroundTimeForStun
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			pedCash
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.pedCash
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			pedHasCash
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.pedHasCash
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			pedType
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.pedType
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			popType
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.popType
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ragdollBlockingFlags
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.ragdollBlockingFlags
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			shootRate
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.shootRate
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			targetLossResponse
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.targetLossResponse
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			uMaxNumFriendsToInform
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.uMaxNumFriendsToInform
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			vehicleweaponindex
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.vehicleweaponindex
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CPedSectorPosMapNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			IsRagdolling
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsRagdolling
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsStandingOnNetworkObject
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsStandingOnNetworkObject
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LocalOffset
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">V3 object.LocalOffset
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			StandingOnNetworkObjectID
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.StandingOnNetworkObjectID
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CPedTaskSequenceDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			hasSequence
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.hasSequence
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			numTasks
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.numTasks
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			repeatMode
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.repeatMode
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			sequenceResourceId
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.sequenceResourceId
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			taskData
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">table<int, CTaskData> object.taskData
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CPedTaskSpecificDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			taskData
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">CTaskData object.taskData
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			taskIndex
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.taskIndex
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CPedTaskTreeDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			scriptCommand
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.scriptCommand
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			taskSlotsUsed
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.taskSlotsUsed
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			taskStage
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.taskStage
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			taskTreeData
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">table<int, TaskSlotData> object.taskTreeData
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CPhysical
	</summary>
	<details style="margin-left:16px;">
		<summary>
			DisableInvincible
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void object:DisableInvincible()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			EnableInvincible
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void object:EnableInvincible()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			FromAddress
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">CPhysical CPhysical.FromAddress(int address)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetAddress
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object:GetAddress()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetAttachmentExtension
		</summary>
		<div style="margin-left:16px;">
			<p>Check if the extension is not nil before using it.</p>
			<pre><code class="language-lua">fwAttachmentEntityExtension object:GetAttachmentExtension()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetType
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">eEntityType object:GetType()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetVelocity
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the current velocity vector in meters per second.</p>
			<pre><code class="language-lua">V3 object:GetVelocity()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HeightMultiplier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.HeightMultiplier
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsDynamic
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsDynamic
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsFixed
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsFixed
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsFixedByNetwork
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsFixedByNetwork
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsInWater
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsInWater
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsInvincible
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsInvincible()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsNotBuoyant
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsNotBuoyant
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsObject
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsObject()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsPed
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsPed()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsPhysical
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsPhysical()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsRenderScorched
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsRenderScorched
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsVehicle
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsVehicle()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsVisible
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsVisible
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ModelInfo
		</summary>
		<div style="margin-left:16px;">
			<p>Check if 'object.ModelInfo' is not nil before using it.</p>
			<pre><code class="language-lua">CBaseModelInfo object.ModelInfo
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NetObject
		</summary>
		<div style="margin-left:16px;">
			<p>Check if 'object.NetObject' is not nil before using it.</p>
			<pre><code class="language-lua">CNetObject object.NetObject
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Position
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">V3 object.Position
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ThicknessMultiplier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.ThicknessMultiplier
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			WidthMultiplier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.WidthMultiplier
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CPhysicalAttachDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			InvMassScaleA
		</summary>
		<div style="margin-left:16px;">
			<p>inv mass scale A</p>
			<pre><code class="language-lua">number object.InvMassScaleA
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			InvMassScaleB
		</summary>
		<div style="margin-left:16px;">
			<p>inv mass scale B</p>
			<pre><code class="language-lua">number object.InvMassScaleB
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsCargoVehicle
		</summary>
		<div style="margin-left:16px;">
			<p>is the vehicle attached as a cargo vehicle</p>
			<pre><code class="language-lua">bool object.IsCargoVehicle
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			activatePhysicsWhenDetached
		</summary>
		<div style="margin-left:16px;">
			<p>activates the physics on the object when it is detached</p>
			<pre><code class="language-lua">bool object.activatePhysicsWhenDetached
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			allowInitialSeparation
		</summary>
		<div style="margin-left:16px;">
			<p>allowed initial separation</p>
			<pre><code class="language-lua">bool object.allowInitialSeparation
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			attached
		</summary>
		<div style="margin-left:16px;">
			<p>is this object attached?</p>
			<pre><code class="language-lua">bool object.attached
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			attachedObjectID
		</summary>
		<div style="margin-left:16px;">
			<p>object ID of the object attached to</p>
			<pre><code class="language-lua">int object.attachedObjectID
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			attachmentFlags
		</summary>
		<div style="margin-left:16px;">
			<p>attachment flags</p>
			<pre><code class="language-lua">int object.attachmentFlags
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			attachmentMyBone
		</summary>
		<div style="margin-left:16px;">
			<p>attachment bone</p>
			<pre><code class="language-lua">int object.attachmentMyBone
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			attachmentOffset
		</summary>
		<div style="margin-left:16px;">
			<p>attachment offset</p>
			<pre><code class="language-lua">V3 object.attachmentOffset
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			attachmentOtherBone
		</summary>
		<div style="margin-left:16px;">
			<p>attachment bone</p>
			<pre><code class="language-lua">int object.attachmentOtherBone
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			attachmentParentOffset
		</summary>
		<div style="margin-left:16px;">
			<p>attachment parent offset</p>
			<pre><code class="language-lua">V3 object.attachmentParentOffset
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			attachmentQuat
		</summary>
		<div style="margin-left:16px;">
			<p>attachment quaternion</p>
			<pre><code class="language-lua">V3 object.attachmentQuat
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			syncPhysicsActivation
		</summary>
		<div style="margin-left:16px;">
			<p>if set m_activatePhysicsWhenDetached is synced</p>
			<pre><code class="language-lua">bool object.syncPhysicsActivation
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CPhysicalGameStateDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			allowCloningWhileInTutorial
		</summary>
		<div style="margin-left:16px;">
			<p>if set, the entity won't be stopped from cloning for players who are not in a tutorial</p>
			<pre><code class="language-lua">bool object.allowCloningWhileInTutorial
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			alphaType
		</summary>
		<div style="margin-left:16px;">
			<p>the type of alpha ramp the entity is doing</p>
			<pre><code class="language-lua">int object.alphaType
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			alteringAlpha
		</summary>
		<div style="margin-left:16px;">
			<p>the entity is fading out / alpha ramping</p>
			<pre><code class="language-lua">bool object.alteringAlpha
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			customFadeDuration
		</summary>
		<div style="margin-left:16px;">
			<p>A custom max duration for fading</p>
			<pre><code class="language-lua">int object.customFadeDuration
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			fadingOut
		</summary>
		<div style="margin-left:16px;">
			<p>the entity is fading out</p>
			<pre><code class="language-lua">bool object.fadingOut
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isInWater
		</summary>
		<div style="margin-left:16px;">
			<p>is in water game state flag</p>
			<pre><code class="language-lua">bool object.isInWater
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isVisible
		</summary>
		<div style="margin-left:16px;">
			<p>gamestate flag indicating whether the object is visible</p>
			<pre><code class="language-lua">bool object.isVisible
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			renderScorched
		</summary>
		<div style="margin-left:16px;">
			<p>render scorched game state flag</p>
			<pre><code class="language-lua">bool object.renderScorched
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CPhysicalMigrationDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			isDead
		</summary>
		<div style="margin-left:16px;">
			<p>does this object have zero health?</p>
			<pre><code class="language-lua">bool object.isDead
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CPickupCreationDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			LODdistance
		</summary>
		<div style="margin-left:16px;">
			<p>LOD distance of pickup</p>
			<pre><code class="language-lua">int object.LODdistance
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PlayersToBlockList
		</summary>
		<div style="margin-left:16px;">
			<p>List of blocked players for this pickup</p>
			<pre><code class="language-lua">int object.PlayersToBlockList
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			amount
		</summary>
		<div style="margin-left:16px;">
			<p>the amount held in the pickup (only used for money pickups currently)</p>
			<pre><code class="language-lua">int object.amount
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bHasPlacement
		</summary>
		<div style="margin-left:16px;">
			<p>set if the network object has a corresponding CPickup object</p>
			<pre><code class="language-lua">bool object.bHasPlacement
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bHasPlayersBlockingList
		</summary>
		<div style="margin-left:16px;">
			<p>Are there any blocked players for this pickup</p>
			<pre><code class="language-lua">bool object.bHasPlayersBlockingList
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bPlayerGift
		</summary>
		<div style="margin-left:16px;">
			<p>set if this is an ambient pickup dropped for another player to collect</p>
			<pre><code class="language-lua">bool object.bPlayerGift
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			customModelHash
		</summary>
		<div style="margin-left:16px;">
			<p>a custom model, if specified by script</p>
			<pre><code class="language-lua">int object.customModelHash
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			includeProjectiles
		</summary>
		<div style="margin-left:16px;">
			<p>Allow projectiles to collide with this pickup</p>
			<pre><code class="language-lua">bool object.includeProjectiles
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			lifeTime
		</summary>
		<div style="margin-left:16px;">
			<p>how long the pickup has existed (only used for ambient pickups)</p>
			<pre><code class="language-lua">int object.lifeTime
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			numWeaponComponents
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.numWeaponComponents
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			pickupHash
		</summary>
		<div style="margin-left:16px;">
			<p>the type of the pickup</p>
			<pre><code class="language-lua">int object.pickupHash
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			weaponComponents
		</summary>
		<div style="margin-left:16px;">
			<p>for modded weapons dropped by players</p>
			<pre><code class="language-lua">table<int, int> object.weaponComponents
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			weaponTintIndex
		</summary>
		<div style="margin-left:16px;">
			<p>for modded weapons dropped by players</p>
			<pre><code class="language-lua">int object.weaponTintIndex
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CPickupPlacementCreationDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			amount
		</summary>
		<div style="margin-left:16px;">
			<p>a variable amount used by some pickup types (eg money).</p>
			<pre><code class="language-lua">int object.amount
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			customModelHash
		</summary>
		<div style="margin-left:16px;">
			<p>a custom model, if specified by script</p>
			<pre><code class="language-lua">int object.customModelHash
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			customRegenTime
		</summary>
		<div style="margin-left:16px;">
			<p>a custom regeneration time, if specified by script</p>
			<pre><code class="language-lua">int object.customRegenTime
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			mapPlacement
		</summary>
		<div style="margin-left:16px;">
			<p>indicates whether this is a map placement or not</p>
			<pre><code class="language-lua">bool object.mapPlacement
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			pickupHash
		</summary>
		<div style="margin-left:16px;">
			<p>the hash of the pickup type</p>
			<pre><code class="language-lua">int object.pickupHash
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			pickupOrientation
		</summary>
		<div style="margin-left:16px;">
			<p>the pickup orientation in eulers</p>
			<pre><code class="language-lua">V3 object.pickupOrientation
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			pickupPosition
		</summary>
		<div style="margin-left:16px;">
			<p>the pickup position</p>
			<pre><code class="language-lua">V3 object.pickupPosition
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			placementFlags
		</summary>
		<div style="margin-left:16px;">
			<p>the placement flags</p>
			<pre><code class="language-lua">int object.placementFlags
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			teamPermits
		</summary>
		<div style="margin-left:16px;">
			<p>which teams are allowed to collect this pickup</p>
			<pre><code class="language-lua">int object.teamPermits
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CPickupSectorPosNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			SectorPosX
		</summary>
		<div style="margin-left:16px;">
			<p>X position of this object within the current sector</p>
			<pre><code class="language-lua">number object.SectorPosX
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SectorPosY
		</summary>
		<div style="margin-left:16px;">
			<p>Y position of this object within the current sector</p>
			<pre><code class="language-lua">number object.SectorPosY
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SectorPosZ
		</summary>
		<div style="margin-left:16px;">
			<p>Z position of this object within the current sector</p>
			<pre><code class="language-lua">number object.SectorPosZ
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CPlaneGameStateDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			AIIgnoresBrokenPartsForHandling
		</summary>
		<div style="margin-left:16px;">
			<p>if AI can fly plane well with damaged parts</p>
			<pre><code class="language-lua">bool object.AIIgnoresBrokenPartsForHandling
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AllowRollAndYawWhenCrashing
		</summary>
		<div style="margin-left:16px;">
			<p>When set, planes will spiral while crashing</p>
			<pre><code class="language-lua">bool object.AllowRollAndYawWhenCrashing
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BrokenSections
		</summary>
		<div style="margin-left:16px;">
			<p>flags indicating which sections have broken off</p>
			<pre><code class="language-lua">int object.BrokenSections
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ControlSectionsBreakOffFromExplosions
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.ControlSectionsBreakOffFromExplosions
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DamagedSections
		</summary>
		<div style="margin-left:16px;">
			<p>flags indicating which sections are damaged</p>
			<pre><code class="language-lua">int object.DamagedSections
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			EngineDamageScale
		</summary>
		<div style="margin-left:16px;">
			<p>damage scale for engine (overall)</p>
			<pre><code class="language-lua">number object.EngineDamageScale
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HasCustomLandingGearSectionDamageScale
		</summary>
		<div style="margin-left:16px;">
			<p>Do we have custom damage scales for our landing gear sections?</p>
			<pre><code class="language-lua">bool object.HasCustomLandingGearSectionDamageScale
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HasCustomSectionDamageScale
		</summary>
		<div style="margin-left:16px;">
			<p>Do we have custom damage scales for our sections?</p>
			<pre><code class="language-lua">bool object.HasCustomSectionDamageScale
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IndividualPropellerFlags
		</summary>
		<div style="margin-left:16px;">
			<p>flags indicating state of individual propellers</p>
			<pre><code class="language-lua">int object.IndividualPropellerFlags
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LODdistance
		</summary>
		<div style="margin-left:16px;">
			<p>LOD distance of pickup</p>
			<pre><code class="language-lua">int object.LODdistance
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LandingGearPublicState
		</summary>
		<div style="margin-left:16px;">
			<p>Landing Gear Public State</p>
			<pre><code class="language-lua">int object.LandingGearPublicState
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LandingGearSectionDamageScale
		</summary>
		<div style="margin-left:16px;">
			<p>damage scale for each plane section</p>
			<pre><code class="language-lua">table<int, number> object.LandingGearSectionDamageScale
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LockOnState
		</summary>
		<div style="margin-left:16px;">
			<p>Lockon state (none, acquiring, acquired)</p>
			<pre><code class="language-lua">int object.LockOnState
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LockOnTarget
		</summary>
		<div style="margin-left:16px;">
			<p>ID of network object this plane is locked-on to</p>
			<pre><code class="language-lua">int object.LockOnTarget
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RotorBroken
		</summary>
		<div style="margin-left:16px;">
			<p>flags indicating which rotors are broken off</p>
			<pre><code class="language-lua">int object.RotorBroken
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SectionDamage
		</summary>
		<div style="margin-left:16px;">
			<p>damage fraction values for each plane section</p>
			<pre><code class="language-lua">table<int, number> object.SectionDamage
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SectionDamageScale
		</summary>
		<div style="margin-left:16px;">
			<p>damage scale for each plane section</p>
			<pre><code class="language-lua">table<int, number> object.SectionDamageScale
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			dipStraightDownWhenCrashing
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.dipStraightDownWhenCrashing
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			disableExlodeFromBodyDamageOnCollision
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.disableExlodeFromBodyDamageOnCollision
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			disableExpFromBodyDamage
		</summary>
		<div style="margin-left:16px;">
			<p>Does this plane take damage from body impacts?</p>
			<pre><code class="language-lua">bool object.disableExpFromBodyDamage
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CPlayerAmbientModelStreamingNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			AllowedPedModelStartOffset
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.AllowedPedModelStartOffset
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AllowedVehicleModelStartOffset
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.AllowedVehicleModelStartOffset
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TargetVehicleEntryPoint
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.TargetVehicleEntryPoint
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TargetVehicleForAnimStreaming
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.TargetVehicleForAnimStreaming
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CPlayerAppearanceDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			HasDecorations
		</summary>
		<div style="margin-left:16px;">
			<p>number of decorations (medals/tattoos)</p>
			<pre><code class="language-lua">bool object.HasDecorations
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HasHeadBlendData
		</summary>
		<div style="margin-left:16px;">
			<p>does this player have custom head data?</p>
			<pre><code class="language-lua">bool object.HasHeadBlendData
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HasRespawnObjId
		</summary>
		<div style="margin-left:16px;">
			<p>has a valid respawn object id</p>
			<pre><code class="language-lua">bool object.HasRespawnObjId
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NewModelHash
		</summary>
		<div style="margin-left:16px;">
			<p>model index for player</p>
			<pre><code class="language-lua">int object.NewModelHash
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PackedDecorations
		</summary>
		<div style="margin-left:16px;">
			<p>texture preset hashes (looked up from collection)</p>
			<pre><code class="language-lua">table<int, int> object.PackedDecorations
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RespawnNetObjId
		</summary>
		<div style="margin-left:16px;">
			<p>ID of the ped used for Team Swapping</p>
			<pre><code class="language-lua">int object.RespawnNetObjId
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			VoiceHash
		</summary>
		<div style="margin-left:16px;">
			<p>voice hash code</p>
			<pre><code class="language-lua">int object.VoiceHash
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			crewEmblemVariation
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.crewEmblemVariation
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			crewLogoTexHash
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.crewLogoTexHash
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			crewLogoTxdHash
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.crewLogoTxdHash
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			facialClipSetId
		</summary>
		<div style="margin-left:16px;">
			<p>the facial clipset used by the player</p>
			<pre><code class="language-lua">int object.facialClipSetId
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			facialIdleAnimOverrideClipDictNameHash
		</summary>
		<div style="margin-left:16px;">
			<p>the dictionary used by the player</p>
			<pre><code class="language-lua">int object.facialIdleAnimOverrideClipDictNameHash
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			facialIdleAnimOverrideClipNameHash
		</summary>
		<div style="margin-left:16px;">
			<p>the facial clip used by the player</p>
			<pre><code class="language-lua">int object.facialIdleAnimOverrideClipNameHash
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			helmetProp
		</summary>
		<div style="margin-left:16px;">
			<p>which helmet prop are we using?</p>
			<pre><code class="language-lua">int object.helmetProp
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			helmetTextureId
		</summary>
		<div style="margin-left:16px;">
			<p>which helmet are we about to put on?</p>
			<pre><code class="language-lua">int object.helmetTextureId
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isAttachingHelmet
		</summary>
		<div style="margin-left:16px;">
			<p>are we attaching a helmet via TaskMotionInAutomobile::State_PutOnHelmet</p>
			<pre><code class="language-lua">bool object.isAttachingHelmet
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isRemovingHelmet
		</summary>
		<div style="margin-left:16px;">
			<p>are we playing secondary priority removing helmet anim?</p>
			<pre><code class="language-lua">bool object.isRemovingHelmet
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isVisorSwitching
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.isVisorSwitching
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isWearingHelmet
		</summary>
		<div style="margin-left:16px;">
			<p>are we wearing a helmet (needed for when we aborting putting one on)</p>
			<pre><code class="language-lua">bool object.isWearingHelmet
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			networkedDamagePack
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.networkedDamagePack
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			parachutePackTintIndex
		</summary>
		<div style="margin-left:16px;">
			<p>Colour of the players' parachute pack</p>
			<pre><code class="language-lua">int object.parachutePackTintIndex
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			parachuteTintIndex
		</summary>
		<div style="margin-left:16px;">
			<p>Colour of the players' parachute</p>
			<pre><code class="language-lua">int object.parachuteTintIndex
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			phoneMode
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.phoneMode
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			supportsVisor
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.supportsVisor
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			targetVisorState
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.targetVisorState
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			visorIsUp
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.visorIsUp
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			visorPropDown
		</summary>
		<div style="margin-left:16px;">
			<p>which helmet prop are we using?</p>
			<pre><code class="language-lua">int object.visorPropDown
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			visorPropUp
		</summary>
		<div style="margin-left:16px;">
			<p>which helmet prop are we using?</p>
			<pre><code class="language-lua">int object.visorPropUp
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CPlayerCameraDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			LookAtPosition
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">V3 object.LookAtPosition
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Position
		</summary>
		<div style="margin-left:16px;">
			<p>the position offset of the camera if aiming - or absolute position if using a free camera</p>
			<pre><code class="language-lua">V3 object.Position
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			UsingCinematicVehCamera
		</summary>
		<div style="margin-left:16px;">
			<p>if set, this player is using the cinematic vehicle camera</p>
			<pre><code class="language-lua">bool object.UsingCinematicVehCamera
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			UsingFreeCamera
		</summary>
		<div style="margin-left:16px;">
			<p>if set, this player is controlling a free camera</p>
			<pre><code class="language-lua">bool object.UsingFreeCamera
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			UsingLeftTriggerAimMode
		</summary>
		<div style="margin-left:16px;">
			<p>is this player using the left trigger aim camera mode</p>
			<pre><code class="language-lua">bool object.UsingLeftTriggerAimMode
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			aiming
		</summary>
		<div style="margin-left:16px;">
			<p>if the player is currently aiming a weapon</p>
			<pre><code class="language-lua">bool object.aiming
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bAimTargetEntity
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bAimTargetEntity
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			canOwnerMoveWhileAiming
		</summary>
		<div style="margin-left:16px;">
			<p>can the owner move while aiming (changes based on aiming from hip / scope / weapon)</p>
			<pre><code class="language-lua">bool object.canOwnerMoveWhileAiming
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			eulersX
		</summary>
		<div style="margin-left:16px;">
			<p>camera matrix euler angles</p>
			<pre><code class="language-lua">number object.eulersX
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			eulersZ
		</summary>
		<div style="margin-left:16px;">
			<p>camera matrix euler angles</p>
			<pre><code class="language-lua">number object.eulersZ
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			freeAimLockedOnTarget
		</summary>
		<div style="margin-left:16px;">
			<p>if the player is free aim locked onto a target...</p>
			<pre><code class="language-lua">bool object.freeAimLockedOnTarget
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			inFirstPersonIdle
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.inFirstPersonIdle
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isLooking
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.isLooking
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			largeOffset
		</summary>
		<div style="margin-left:16px;">
			<p>if set, the camera is far away from the player</p>
			<pre><code class="language-lua">bool object.largeOffset
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			lockOnTargetOffset
		</summary>
		<div style="margin-left:16px;">
			<p>if locked onto a target, offset from target position to actual lock on pos.</p>
			<pre><code class="language-lua">V3 object.lockOnTargetOffset
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			longRange
		</summary>
		<div style="margin-left:16px;">
			<p>if the player is aiming a long range weapon (sniper rifle - 1500m range) or short range (<150m)</p>
			<pre><code class="language-lua">bool object.longRange
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			morePrecision
		</summary>
		<div style="margin-left:16px;">
			<p>if set, more precise camera data is used</p>
			<pre><code class="language-lua">bool object.morePrecision
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			onSlope
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.onSlope
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			playerToTargetAimOffset
		</summary>
		<div style="margin-left:16px;">
			<p>position we're aiming at (used to compute pitch and yaw on the clone).</p>
			<pre><code class="language-lua">V3 object.playerToTargetAimOffset
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			stickWithinStrafeAngle
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.stickWithinStrafeAngle
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			targetId
		</summary>
		<div style="margin-left:16px;">
			<p>if we're aiming at a target we pass that info instead of pitch and yaw.</p>
			<pre><code class="language-lua">int object.targetId
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			usingFirstPersonCamera
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.usingFirstPersonCamera
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			usingFirstPersonVehicleCamera
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.usingFirstPersonVehicleCamera
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			usingSwimMotionTask
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.usingSwimMotionTask
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CPlayerCreationDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			ModelHash
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.ModelHash
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NumBloodMarks
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.NumBloodMarks
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NumScars
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.NumScars
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			hasCommunicationPrivileges
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.hasCommunicationPrivileges
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			wearingAHelmet
		</summary>
		<div style="margin-left:16px;">
			<p>only want to apply this once and then it's derived locally...</p>
			<pre><code class="language-lua">bool object.wearingAHelmet
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CPlayerGameStateDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			AirDragMult
		</summary>
		<div style="margin-left:16px;">
			<p>air drag multiplier</p>
			<pre><code class="language-lua">number object.AirDragMult
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AntagonisticPlayerIndex
		</summary>
		<div style="margin-left:16px;">
			<p>Antagonistic player index</p>
			<pre><code class="language-lua">int object.AntagonisticPlayerIndex
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ConcealedOnOwner
		</summary>
		<div style="margin-left:16px;">
			<p>true when local player concealed themselves</p>
			<pre><code class="language-lua">bool object.ConcealedOnOwner
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			EnableCrewEmblem
		</summary>
		<div style="margin-left:16px;">
			<p>Does the ped use the crew emblem?</p>
			<pre><code class="language-lua">bool object.EnableCrewEmblem
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			FadeOut
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.FadeOut
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GameStateFlags
		</summary>
		<div style="margin-left:16px;">
			<p>game state flags</p>
			<pre><code class="language-lua">PlayerGameStateFlags object.GameStateFlags
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GarageInstanceIndex
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.GarageInstanceIndex
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsTargettableByTeam
		</summary>
		<div style="margin-left:16px;">
			<p>flags indicating whether the ped is targettable by each team //</p>
			<pre><code class="language-lua">int object.IsTargettableByTeam
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			JackSpeed
		</summary>
		<div style="margin-left:16px;">
			<p>jack speed percentage for the player</p>
			<pre><code class="language-lua">int object.JackSpeed
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LockOnState
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.LockOnState
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LockOnTargetID
		</summary>
		<div style="margin-left:16px;">
			<p>for when players use homing launchers</p>
			<pre><code class="language-lua">int object.LockOnTargetID
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			MaxArmour
		</summary>
		<div style="margin-left:16px;">
			<p>max armour for the player</p>
			<pre><code class="language-lua">int object.MaxArmour
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			MaxHealth
		</summary>
		<div style="margin-left:16px;">
			<p>max health for the player</p>
			<pre><code class="language-lua">int object.MaxHealth
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			MeleeDamageModifier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.MeleeDamageModifier
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			MeleeUnarmedDamageModifier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.MeleeUnarmedDamageModifier
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			MobileRingState
		</summary>
		<div style="margin-left:16px;">
			<p>mobile phone ring state for the player</p>
			<pre><code class="language-lua">int object.MobileRingState
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			OverrideReceiveChat
		</summary>
		<div style="margin-left:16px;">
			<p>Override Receive Chat</p>
			<pre><code class="language-lua">int object.OverrideReceiveChat
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			OverrideSendChat
		</summary>
		<div style="margin-left:16px;">
			<p>Override Send Chat //</p>
			<pre><code class="language-lua">int object.OverrideSendChat
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PlayerState
		</summary>
		<div style="margin-left:16px;">
			<p>the current player state</p>
			<pre><code class="language-lua">int object.PlayerState
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PlayerTeam
		</summary>
		<div style="margin-left:16px;">
			<p>current player team</p>
			<pre><code class="language-lua">int object.PlayerTeam
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ScriptedWeaponFirePos
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">V3 object.ScriptedWeaponFirePos
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SpectatorId
		</summary>
		<div style="margin-left:16px;">
			<p>Network Object of the ped we are spectating</p>
			<pre><code class="language-lua">int object.SpectatorId
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TutorialIndex
		</summary>
		<div style="margin-left:16px;">
			<p>Tutorial session index - used to split players into fake sessions including only team-mates</p>
			<pre><code class="language-lua">int object.TutorialIndex
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TutorialInstanceID
		</summary>
		<div style="margin-left:16px;">
			<p>Current tutorial instance ID (only used for gang sessions)</p>
			<pre><code class="language-lua">int object.TutorialInstanceID
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			VehicleJumpDown
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.VehicleJumpDown
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			VehicleShareMultiplier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.VehicleShareMultiplier
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			WeaponDamageModifier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.WeaponDamageModifier
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			WeaponDefenseModifier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.WeaponDefenseModifier
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			WeaponMinigunDefenseModifier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.WeaponMinigunDefenseModifier
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			arcadeCNCVOffender
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.arcadeCNCVOffender
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			arcadePassiveAbilityFlags
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.arcadePassiveAbilityFlags
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			arcadeRoleInt
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.arcadeRoleInt
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			arcadeTeamInt
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.arcadeTeamInt
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bBattleAware
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bBattleAware
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bCollisionsDisabledByScript
		</summary>
		<div style="margin-left:16px;">
			<p>used for spectating players, that have other collision flags set</p>
			<pre><code class="language-lua">bool object.bCollisionsDisabledByScript
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bDisableLeavePedBehind
		</summary>
		<div style="margin-left:16px;">
			<p>Disable Leave ped behind when the remote player leaves the session.</p>
			<pre><code class="language-lua">bool object.bDisableLeavePedBehind
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bGhost
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bGhost
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bHasScriptedWeaponFirePos
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bHasScriptedWeaponFirePos
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bHasVoiceProximityOverride
		</summary>
		<div style="margin-left:16px;">
			<p>If we have a voice proximity override</p>
			<pre><code class="language-lua">bool object.bHasVoiceProximityOverride
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bInCutscene
		</summary>
		<div style="margin-left:16px;">
			<p>player is in a mocap cutscene</p>
			<pre><code class="language-lua">bool object.bInCutscene
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bIsChokingFromDOTEffect
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bIsChokingFromDOTEffect
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bIsFriendlyFireAllowed
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bIsFriendlyFireAllowed
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bIsPassiveMode
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bIsPassiveMode
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bIsSCTVSpectating
		</summary>
		<div style="margin-left:16px;">
			<p>true when player is SCTV spectator</p>
			<pre><code class="language-lua">bool object.bIsSCTVSpectating
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bIsShockedFromDOTEffect
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bIsShockedFromDOTEffect
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bIsSuperJump
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bIsSuperJump
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bOverrideTransitionChat
		</summary>
		<div style="margin-left:16px;">
			<p>Override Transition Chat</p>
			<pre><code class="language-lua">bool object.bOverrideTransitionChat
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bOverrideTutorialChat
		</summary>
		<div style="margin-left:16px;">
			<p>Override Tutorial Chat</p>
			<pre><code class="language-lua">bool object.bOverrideTutorialChat
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bUseExtendedPopulationRange
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bUseExtendedPopulationRange
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bvehicleweaponindex
		</summary>
		<div style="margin-left:16px;">
			<p>Indicator whether the VWI is sent</p>
			<pre><code class="language-lua">bool object.bvehicleweaponindex
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			decoratorListCount
		</summary>
		<div style="margin-left:16px;">
			<p>count of decorator extensions ( the scripted ones )</p>
			<pre><code class="language-lua">int object.decoratorListCount
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			fVoiceLoudness
		</summary>
		<div style="margin-left:16px;">
			<p>Loudness of player voice through microphone</p>
			<pre><code class="language-lua">number object.fVoiceLoudness
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			nCharacterRank
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.nCharacterRank
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			nMentalState
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.nMentalState
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			nPedDensity
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.nPedDensity
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			nPropertyID
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.nPropertyID
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			nVoiceChannel
		</summary>
		<div style="margin-left:16px;">
			<p>Voice channel this player is in</p>
			<pre><code class="language-lua">int object.nVoiceChannel
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			sizeOfNetArrayData
		</summary>
		<div style="margin-left:16px;">
			<p>the total size of all the network array handler data arbitrated by this player</p>
			<pre><code class="language-lua">int object.sizeOfNetArrayData
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			vExtendedPopulationRangeCenter
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">V3 object.vExtendedPopulationRangeCenter
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			vVoiceProximityOverride
		</summary>
		<div style="margin-left:16px;">
			<p>Proximity override</p>
			<pre><code class="language-lua">V3 object.vVoiceProximityOverride
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			vehicleweaponindex
		</summary>
		<div style="margin-left:16px;">
			<p>Vehicle Weapon Index: Missiles, Gatling, etc...</p>
			<pre><code class="language-lua">int object.vehicleweaponindex
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CPlayerInfo
	</summary>
	<details style="margin-left:16px;">
		<summary>
			CachedSprintMultThisFrame
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.CachedSprintMultThisFrame
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ExplosiveDamageModifier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.ExplosiveDamageModifier
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ForceAirDragMult
		</summary>
		<div style="margin-left:16px;">
			<p>Affects the air drag of the player's current car/bike</p>
			<pre><code class="language-lua">number object.ForceAirDragMult
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			FriendStatus
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.FriendStatus
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HavocCaused
		</summary>
		<div style="margin-left:16px;">
			<p>A counter going up when the player does bad stuff.</p>
			<pre><code class="language-lua">int object.HavocCaused
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			JackSpeed
		</summary>
		<div style="margin-left:16px;">
			<p>2 bytes</p>
			<pre><code class="language-lua">int object.JackSpeed
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LastChangeWeaponFrame
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.LastChangeWeaponFrame
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LastTargetVehicle
		</summary>
		<div style="margin-left:16px;">
			<p>Last vehicle player tried to enter.</p>
			<pre><code class="language-lua">CVehicle object.LastTargetVehicle
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			MaxArmour
		</summary>
		<div style="margin-left:16px;">
			<p>2 bytes</p>
			<pre><code class="language-lua">int object.MaxArmour
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			MaxExplosiveDamage
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.MaxExplosiveDamage
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			MaxHealth
		</summary>
		<div style="margin-left:16px;">
			<p>2 bytes</p>
			<pre><code class="language-lua">int object.MaxHealth
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			MaxSprintEnergy
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.MaxSprintEnergy
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			MeleeUnarmedDamageModifier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.MeleeUnarmedDamageModifier
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			MeleeWeaponDamageModifier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.MeleeWeaponDamageModifier
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			MeleeWeaponDefenseModifier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.MeleeWeaponDefenseModifier
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			MeleeWeaponForceModifier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.MeleeWeaponForceModifier
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NetData
		</summary>
		<div style="margin-left:16px;">
			<p>structure to GamerInfo holding information about the player</p>
			<pre><code class="language-lua">GamerInfo object.NetData
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NumEnemiesInCombat
		</summary>
		<div style="margin-left:16px;">
			<p>A count of the number of enemy peds in combat targetting this player.</p>
			<pre><code class="language-lua">int object.NumEnemiesInCombat
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NumEnemiesShootingInCombat
		</summary>
		<div style="margin-left:16px;">
			<p>A count of the number of enemy peds shooting at this player.</p>
			<pre><code class="language-lua">int object.NumEnemiesShootingInCombat
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			OnlyEnterThisVehicle
		</summary>
		<div style="margin-left:16px;">
			<p>Restrict the player to only being able to enter this vehicle (script-controlled)	</p>
			<pre><code class="language-lua">CVehicle object.OnlyEnterThisVehicle
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PlayerGroup
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.PlayerGroup
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PlayerPed
		</summary>
		<div style="margin-left:16px;">
			<p>Pointer to the player ped (should always be set)</p>
			<pre><code class="language-lua">CPed object.PlayerPed
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PlayerState
		</summary>
		<div style="margin-left:16px;">
			<p>PLAYERSTATE_INVALID = -1, PLAYERSTATE_PLAYING, PLAYERSTATE_HASDIED, PLAYERSTATE_HASBEENARRESTED, PLAYERSTATE_FAILEDMISSION, PLAYERSTATE_LEFTGAME, PLAYERSTATE_RESPAWN, PLAYERSTATE_IN_MP_CUTSCENE</p>
			<pre><code class="language-lua">int object.PlayerState
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PreferFrontPassengerSeatVehicle
		</summary>
		<div style="margin-left:16px;">
			<p>Script can prefer the player to enter the front passenger seat for this vehicle</p>
			<pre><code class="language-lua">CVehicle object.PreferFrontPassengerSeatVehicle
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PreferRearSeatsVehicle
		</summary>
		<div style="margin-left:16px;">
			<p>Script can prefer the player to enter the rear seats for this vehicle</p>
			<pre><code class="language-lua">CVehicle object.PreferRearSeatsVehicle
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RunSprintSpeedMultiplier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.RunSprintSpeedMultiplier
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SpotterOfStolenVehicle
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">CPed object.SpotterOfStolenVehicle
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SprintControlCounter
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.SprintControlCounter
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SprintEnergy
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.SprintEnergy
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			StealthRate
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.StealthRate
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SwimSpeedMultiplier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.SwimSpeedMultiplier
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Team
		</summary>
		<div style="margin-left:16px;">
			<p>The player's team (in network game)</p>
			<pre><code class="language-lua">int object.Team
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TimeBikeSprintPressed
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.TimeBikeSprintPressed
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			VehicleDamageModifier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.VehicleDamageModifier
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			VehicleDefenseModifier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.VehicleDefenseModifier
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			WeaponDamageModifier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.WeaponDamageModifier
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			WeaponDefenseModifier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.WeaponDefenseModifier
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			WeaponMinigunDefenseModifier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.WeaponMinigunDefenseModifier
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			WeaponTakedownDefenseModifier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.WeaponTakedownDefenseModifier
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CPlayerSectorPosNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			IsOnStairs
		</summary>
		<div style="margin-left:16px;">
			<p>is this player standing on stairs?</p>
			<pre><code class="language-lua">bool object.IsOnStairs
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsRagdolling
		</summary>
		<div style="margin-left:16px;">
			<p>is this player ragdolling?</p>
			<pre><code class="language-lua">bool object.IsRagdolling
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsStandingOnNetworkObject
		</summary>
		<div style="margin-left:16px;">
			<p>is this player currently standing on another network object?</p>
			<pre><code class="language-lua">bool object.IsStandingOnNetworkObject
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LocalOffset
		</summary>
		<div style="margin-left:16px;">
			<p>Offset from the center of the object</p>
			<pre><code class="language-lua">V3 object.LocalOffset
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PackedStealthNoise
		</summary>
		<div style="margin-left:16px;">
			<p>the serialised players current stealth noise</p>
			<pre><code class="language-lua">int object.PackedStealthNoise
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SectorPosX
		</summary>
		<div style="margin-left:16px;">
			<p>X position of this object within the current sector</p>
			<pre><code class="language-lua">number object.SectorPosX
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SectorPosY
		</summary>
		<div style="margin-left:16px;">
			<p>Y position of this object within the current sector</p>
			<pre><code class="language-lua">number object.SectorPosY
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SectorPosZ
		</summary>
		<div style="margin-left:16px;">
			<p>Z position of this object within the current sector</p>
			<pre><code class="language-lua">number object.SectorPosZ
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			StandingOnNetworkObjectID
		</summary>
		<div style="margin-left:16px;">
			<p>ID of the object this player is standing on</p>
			<pre><code class="language-lua">int object.StandingOnNetworkObjectID
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			StealthNoise
		</summary>
		<div style="margin-left:16px;">
			<p>the players current stealth noise</p>
			<pre><code class="language-lua">number object.StealthNoise
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CSectorDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			sectorX
		</summary>
		<div style="margin-left:16px;">
			<p>X sector this object is currently within</p>
			<pre><code class="language-lua">int object.sectorX
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			sectorY
		</summary>
		<div style="margin-left:16px;">
			<p>Y sector this object is currently within</p>
			<pre><code class="language-lua">int object.sectorY
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			sectorZ
		</summary>
		<div style="margin-left:16px;">
			<p>Z sector this object is currently within</p>
			<pre><code class="language-lua">int object.sectorZ
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CSectorPositionDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			sectorPosX
		</summary>
		<div style="margin-left:16px;">
			<p>X position of this object within the current sector</p>
			<pre><code class="language-lua">number object.sectorPosX
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			sectorPosY
		</summary>
		<div style="margin-left:16px;">
			<p>Y position of this object within the current sector</p>
			<pre><code class="language-lua">number object.sectorPosY
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			sectorPosZ
		</summary>
		<div style="margin-left:16px;">
			<p>Z position of this object within the current sector</p>
			<pre><code class="language-lua">number object.sectorPosZ
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CSubmarineControlDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			dive
		</summary>
		<div style="margin-left:16px;">
			<p>the current value of the dive control.</p>
			<pre><code class="language-lua">number object.dive
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			pitch
		</summary>
		<div style="margin-left:16px;">
			<p>the current value of the pitch control.</p>
			<pre><code class="language-lua">number object.pitch
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			yaw
		</summary>
		<div style="margin-left:16px;">
			<p>the current value of the yaw control.</p>
			<pre><code class="language-lua">number object.yaw
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CSubmarineGameStateDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			IsAnchored
		</summary>
		<div style="margin-left:16px;">
			<p>is this submarine anchored?</p>
			<pre><code class="language-lua">bool object.IsAnchored
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CTaskData
	</summary>
	<details style="margin-left:16px;">
		<summary>
			TaskData
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">table<int, int> object.TaskData
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TaskDataSize
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.TaskDataSize
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TaskType
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.TaskType
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CTrainGameStateDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			AllowRemovalByPopulation
		</summary>
		<div style="margin-left:16px;">
			<p>used by stationary trains in missions</p>
			<pre><code class="language-lua">bool object.AllowRemovalByPopulation
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CarriageConfigIndex
		</summary>
		<div style="margin-left:16px;">
			<p>Config index of the carriage</p>
			<pre><code class="language-lua">int object.CarriageConfigIndex
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CruiseSpeed
		</summary>
		<div style="margin-left:16px;">
			<p>the target cruise speed of the train (desired speed)</p>
			<pre><code class="language-lua">number object.CruiseSpeed
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Direction
		</summary>
		<div style="margin-left:16px;">
			<p>Direction traveling on track</p>
			<pre><code class="language-lua">bool object.Direction
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DistFromEngine
		</summary>
		<div style="margin-left:16px;">
			<p>the distance of this carriage from the engine (0.0 if this is an engine)</p>
			<pre><code class="language-lua">number object.DistFromEngine
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			EngineID
		</summary>
		<div style="margin-left:16px;">
			<p>ID of the engine this carriage is attached to (if this train is not an engine)</p>
			<pre><code class="language-lua">int object.EngineID
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HasPassengerCarriages
		</summary>
		<div style="margin-left:16px;">
			<p>Does this train have any passenger carriages?</p>
			<pre><code class="language-lua">bool object.HasPassengerCarriages
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsCaboose
		</summary>
		<div style="margin-left:16px;">
			<p>Is this a caboose</p>
			<pre><code class="language-lua">bool object.IsCaboose
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsEngine
		</summary>
		<div style="margin-left:16px;">
			<p>is this train an engine or carriage?</p>
			<pre><code class="language-lua">bool object.IsEngine
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsMissionTrain
		</summary>
		<div style="margin-left:16px;">
			<p>Is this a mission created train?</p>
			<pre><code class="language-lua">bool object.IsMissionTrain
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LinkedToBackwardID
		</summary>
		<div style="margin-left:16px;">
			<p>ID of the car linked backward from this train car</p>
			<pre><code class="language-lua">int object.LinkedToBackwardID
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LinkedToForwardID
		</summary>
		<div style="margin-left:16px;">
			<p>ID of the car linked forward from this train car</p>
			<pre><code class="language-lua">int object.LinkedToForwardID
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RenderDerailed
		</summary>
		<div style="margin-left:16px;">
			<p>Should this train be rendered as derailed?</p>
			<pre><code class="language-lua">bool object.RenderDerailed
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			StopForStations
		</summary>
		<div style="margin-left:16px;">
			<p>Stop for stations</p>
			<pre><code class="language-lua">bool object.StopForStations
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TrackID
		</summary>
		<div style="margin-left:16px;">
			<p>the track the train is on</p>
			<pre><code class="language-lua">int object.TrackID
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TrainConfigIndex
		</summary>
		<div style="margin-left:16px;">
			<p>Config index of the entire train this carriage/engine is a part of</p>
			<pre><code class="language-lua">int object.TrainConfigIndex
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TrainState
		</summary>
		<div style="margin-left:16px;">
			<p>the train state</p>
			<pre><code class="language-lua">int object.TrainState
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			UseHighPrecisionBlending
		</summary>
		<div style="margin-left:16px;">
			<p>are we using high precision blending on the train</p>
			<pre><code class="language-lua">bool object.UseHighPrecisionBlending
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			doorsForcedOpen
		</summary>
		<div style="margin-left:16px;">
			<p>force the doors open</p>
			<pre><code class="language-lua">bool object.doorsForcedOpen
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CVehicle
	</summary>
	<details style="margin-left:16px;">
		<summary>
			BodyDirtColor
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.BodyDirtColor
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BodyHealth
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.BodyHealth
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Brake
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.Brake
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CheatPowerIncrease
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.CheatPowerIncrease
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DirtLevel
		</summary>
		<div style="margin-left:16px;">
			<p>0.0=fully clean, 15.0=maximum dirt visible</p>
			<pre><code class="language-lua">number object.DirtLevel
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DisableInvincible
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void object:DisableInvincible()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			EnableInvincible
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void object:EnableInvincible()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			FromAddress
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">CVehicle CVehicle.FromAddress(int address)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetAddress
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object:GetAddress()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetAttachmentExtension
		</summary>
		<div style="margin-left:16px;">
			<p>Check if the extension is not nil before using it.</p>
			<pre><code class="language-lua">fwAttachmentEntityExtension object:GetAttachmentExtension()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetDriver
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">CPed object:GetDriver()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetLastDriver
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">CPed object:GetLastDriver()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetMaxSeats
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object:GetMaxSeats()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetPedInSeat
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">CPed object:GetPedInSeat(int seatIndex)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetType
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">eEntityType object:GetType()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetVelocity
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the current velocity vector in meters per second.</p>
			<pre><code class="language-lua">V3 object:GetVelocity()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HandBrake
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.HandBrake
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HeadlightMultiplier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.HeadlightMultiplier
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HeightMultiplier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.HeightMultiplier
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsDynamic
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsDynamic
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsFixed
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsFixed
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsFixedByNetwork
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsFixedByNetwork
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsInWater
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsInWater
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsInvincible
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsInvincible()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsNotBuoyant
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsNotBuoyant
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsObject
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsObject()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsPed
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsPed()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsPhysical
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsPhysical()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsRenderScorched
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsRenderScorched
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsVehicle
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsVehicle()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsVisible
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsVisible
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ModelInfo
		</summary>
		<div style="margin-left:16px;">
			<p>Check if 'object.ModelInfo' is not nil before using it.</p>
			<pre><code class="language-lua">CBaseModelInfo object.ModelInfo
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NetObject
		</summary>
		<div style="margin-left:16px;">
			<p>Check if 'object.NetObject' is not nil before using it.</p>
			<pre><code class="language-lua">CNetObject object.NetObject
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Nitrous
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.Nitrous
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PetrolTankHealth
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.PetrolTankHealth
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Position
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">V3 object.Position
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SecondSteerAngle
		</summary>
		<div style="margin-left:16px;">
			<p>This is for 4 wheel steering.</p>
			<pre><code class="language-lua">number object.SecondSteerAngle
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SteerAngle
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.SteerAngle
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ThicknessMultiplier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.ThicknessMultiplier
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Throttle
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.Throttle
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			VehicleTopSpeedPercent
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.VehicleTopSpeedPercent
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			WidthMultiplier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.WidthMultiplier
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CVehicleAppearanceDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			LicencePlateTexIndex
		</summary>
		<div style="margin-left:16px;">
			<p>Licence plate texture index.</p>
			<pre><code class="language-lua">int object.LicencePlateTexIndex
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			VehicleBadge
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.VehicleBadge
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			allKitMods
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">table<int, int> object.allKitMods
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bSmokeColor
		</summary>
		<div style="margin-left:16px;">
			<p>has a smoke color</p>
			<pre><code class="language-lua">bool object.bSmokeColor
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bVehicleBadgeData
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">table<int, bool> object.bVehicleBadgeData
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bWindowTint
		</summary>
		<div style="margin-left:16px;">
			<p>has a window tint</p>
			<pre><code class="language-lua">bool object.bWindowTint
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bodyColour1
		</summary>
		<div style="margin-left:16px;">
			<p>vehicle body colour 1</p>
			<pre><code class="language-lua">int object.bodyColour1
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bodyColour2
		</summary>
		<div style="margin-left:16px;">
			<p>vehicle body colour 2</p>
			<pre><code class="language-lua">int object.bodyColour2
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bodyColour3
		</summary>
		<div style="margin-left:16px;">
			<p>vehicle body colour 3</p>
			<pre><code class="language-lua">int object.bodyColour3
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bodyColour4
		</summary>
		<div style="margin-left:16px;">
			<p>vehicle body colour 4</p>
			<pre><code class="language-lua">int object.bodyColour4
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bodyColour5
		</summary>
		<div style="margin-left:16px;">
			<p>vehicle body colour 5</p>
			<pre><code class="language-lua">int object.bodyColour5
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bodyColour6
		</summary>
		<div style="margin-left:16px;">
			<p>vehicle body colour 6</p>
			<pre><code class="language-lua">int object.bodyColour6
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bodyDirtLevel
		</summary>
		<div style="margin-left:16px;">
			<p>vehicle body dirt level</p>
			<pre><code class="language-lua">int object.bodyDirtLevel
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			customPrimaryB
		</summary>
		<div style="margin-left:16px;">
			<p>custom secondary color B</p>
			<pre><code class="language-lua">int object.customPrimaryB
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			customPrimaryColor
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.customPrimaryColor
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			customPrimaryG
		</summary>
		<div style="margin-left:16px;">
			<p>custom secondary color G</p>
			<pre><code class="language-lua">int object.customPrimaryG
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			customPrimaryR
		</summary>
		<div style="margin-left:16px;">
			<p>custom secondary color R</p>
			<pre><code class="language-lua">int object.customPrimaryR
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			customSecondaryB
		</summary>
		<div style="margin-left:16px;">
			<p>custom secondary color B</p>
			<pre><code class="language-lua">int object.customSecondaryB
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			customSecondaryColor
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.customSecondaryColor
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			customSecondaryG
		</summary>
		<div style="margin-left:16px;">
			<p>custom secondary color G</p>
			<pre><code class="language-lua">int object.customSecondaryG
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			customSecondaryR
		</summary>
		<div style="margin-left:16px;">
			<p>custom secondary color R</p>
			<pre><code class="language-lua">int object.customSecondaryR
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			disableExtras
		</summary>
		<div style="margin-left:16px;">
			<p>bit flags indicating which "extra" car parts are disabled</p>
			<pre><code class="language-lua">int object.disableExtras
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			envEffScale
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.envEffScale
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			hasDifferentRearWheel
		</summary>
		<div style="margin-left:16px;">
			<p>has a rear wheel that might have a different type (bikes)</p>
			<pre><code class="language-lua">bool object.hasDifferentRearWheel
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			hasLivery2ID
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.hasLivery2ID
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			hasLiveryID
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.hasLiveryID
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			horntype
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.horntype
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			kitIndex
		</summary>
		<div style="margin-left:16px;">
			<p>the kit index that the variation data is using</p>
			<pre><code class="language-lua">int object.kitIndex
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			licencePlate
		</summary>
		<div style="margin-left:16px;">
			<p>Licence Plate</p>
			<pre><code class="language-lua">table<int, int> object.licencePlate
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			livery2ID
		</summary>
		<div style="margin-left:16px;">
			<p>ID of the livery2 for the vehicle</p>
			<pre><code class="language-lua">int object.livery2ID
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			liveryID
		</summary>
		<div style="margin-left:16px;">
			<p>ID of the livery for the vehicle</p>
			<pre><code class="language-lua">int object.liveryID
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			neonBOn
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.neonBOn
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			neonColorB
		</summary>
		<div style="margin-left:16px;">
			<p>neon color B</p>
			<pre><code class="language-lua">int object.neonColorB
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			neonColorG
		</summary>
		<div style="margin-left:16px;">
			<p>neon color G</p>
			<pre><code class="language-lua">int object.neonColorG
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			neonColorR
		</summary>
		<div style="margin-left:16px;">
			<p>neon color R</p>
			<pre><code class="language-lua">int object.neonColorR
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			neonFOn
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.neonFOn
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			neonLOn
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.neonLOn
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			neonOn
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.neonOn
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			neonROn
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.neonROn
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			neonSuppressed
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.neonSuppressed
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			rearWheelMod
		</summary>
		<div style="margin-left:16px;">
			<p>rear wheel mod value (for bikes)</p>
			<pre><code class="language-lua">int object.rearWheelMod
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			smokeColorB
		</summary>
		<div style="margin-left:16px;">
			<p>smoke color B</p>
			<pre><code class="language-lua">int object.smokeColorB
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			smokeColorG
		</summary>
		<div style="margin-left:16px;">
			<p>smoke color G</p>
			<pre><code class="language-lua">int object.smokeColorG
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			smokeColorR
		</summary>
		<div style="margin-left:16px;">
			<p>smoke color R</p>
			<pre><code class="language-lua">int object.smokeColorR
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			toggleMods
		</summary>
		<div style="margin-left:16px;">
			<p>bitfield of the toggle mods that are switched on</p>
			<pre><code class="language-lua">int object.toggleMods
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			wheelMod
		</summary>
		<div style="margin-left:16px;">
			<p>wheel mod value</p>
			<pre><code class="language-lua">int object.wheelMod
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			wheelType
		</summary>
		<div style="margin-left:16px;">
			<p>wheel type value</p>
			<pre><code class="language-lua">int object.wheelType
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			wheelVariation0
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.wheelVariation0
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			wheelVariation1
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.wheelVariation1
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			windowTint
		</summary>
		<div style="margin-left:16px;">
			<p>window tint</p>
			<pre><code class="language-lua">int object.windowTint
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CVehicleControlDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			BVTHControlVertVel
		</summary>
		<div style="margin-left:16px;">
			<p>CTaskBringVehicleToHalt bControlVerticalVelocity</p>
			<pre><code class="language-lua">bool object.BVTHControlVertVel
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BVTHStoppingDist
		</summary>
		<div style="margin-left:16px;">
			<p>CTaskBringVehicleToHalt stopping dist</p>
			<pre><code class="language-lua">number object.BVTHStoppingDist
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HasTargetGravityScale
		</summary>
		<div style="margin-left:16px;">
			<p>For hover vehicles</p>
			<pre><code class="language-lua">bool object.HasTargetGravityScale
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HasTopSpeedPercentage
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.HasTopSpeedPercentage
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			StickY
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.StickY
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SubCarDive
		</summary>
		<div style="margin-left:16px;">
			<p>the current value of the dive control for sub cars</p>
			<pre><code class="language-lua">number object.SubCarDive
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SubCarPitch
		</summary>
		<div style="margin-left:16px;">
			<p>the current value of the pitch control for sub cars</p>
			<pre><code class="language-lua">number object.SubCarPitch
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TargetGravityScale
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.TargetGravityScale
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bAllLowriderHydraulicsRaised
		</summary>
		<div style="margin-left:16px;">
			<p>CTaskVehiclePlayerDriveAutomobile::ProcessDriverInputsForPlayerOnUpdate; player has raised all lowrider suspension</p>
			<pre><code class="language-lua">bool object.bAllLowriderHydraulicsRaised
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bIsClosingAnyDoor
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bIsClosingAnyDoor
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bIsNitrousOverrideActive
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bIsNitrousOverrideActive
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bModifiedLowriderSuspension
		</summary>
		<div style="margin-left:16px;">
			<p>CTaskVehiclePlayerDriveAutomobile::ProcessDriverInputsForPlayerOnUpdate; player has modified suspension of lowrider</p>
			<pre><code class="language-lua">bool object.bModifiedLowriderSuspension
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bNitrousActive
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bNitrousActive
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bPlayHydraulicsActivationSound
		</summary>
		<div style="margin-left:16px;">
			<p>Hydraulics sound effect when activated</p>
			<pre><code class="language-lua">bool object.bPlayHydraulicsActivationSound
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bPlayHydraulicsBounceSound
		</summary>
		<div style="margin-left:16px;">
			<p>Hydraulics sound effect when bouncing</p>
			<pre><code class="language-lua">bool object.bPlayHydraulicsBounceSound
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bPlayHydraulicsDeactivationSound
		</summary>
		<div style="margin-left:16px;">
			<p>Hydraulics sound effect when de-activated</p>
			<pre><code class="language-lua">bool object.bPlayHydraulicsDeactivationSound
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			brakePedal
		</summary>
		<div style="margin-left:16px;">
			<p>the current value of the brake pedal</p>
			<pre><code class="language-lua">number object.brakePedal
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bringVehicleToHalt
		</summary>
		<div style="margin-left:16px;">
			<p>CTaskBringVehicleToHalt is running as a secondary task</p>
			<pre><code class="language-lua">bool object.bringVehicleToHalt
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			fLowriderSuspension
		</summary>
		<div style="margin-left:16px;">
			<p>Syncs modified lowrider suspension values</p>
			<pre><code class="language-lua">table<int, number> object.fLowriderSuspension
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isInBurnout
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.isInBurnout
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isSubCar
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.isSubCar
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			kersActive
		</summary>
		<div style="margin-left:16px;">
			<p>indicates if the kers system is active</p>
			<pre><code class="language-lua">bool object.kersActive
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			numWheels
		</summary>
		<div style="margin-left:16px;">
			<p>number of wheels on this car</p>
			<pre><code class="language-lua">int object.numWheels
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			reducedSuspensionForce
		</summary>
		<div style="margin-left:16px;">
			<p>reduced suspension force used to "stance" tuner pack vehicles</p>
			<pre><code class="language-lua">bool object.reducedSuspensionForce
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			roadNodeAddress
		</summary>
		<div style="margin-left:16px;">
			<p>the current road node the vehicle is driving from</p>
			<pre><code class="language-lua">int object.roadNodeAddress
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			subCarYaw
		</summary>
		<div style="margin-left:16px;">
			<p>the current value of the yaw control for sub cars</p>
			<pre><code class="language-lua">number object.subCarYaw
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			throttle
		</summary>
		<div style="margin-left:16px;">
			<p>the current value of the throttle</p>
			<pre><code class="language-lua">number object.throttle
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			topSpeedPercent
		</summary>
		<div style="margin-left:16px;">
			<p>set to the maximum speed a vehicle can travel at</p>
			<pre><code class="language-lua">number object.topSpeedPercent
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CVehicleCreationDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			lastDriverTime
		</summary>
		<div style="margin-left:16px;">
			<p>the last time this vehicle had a driver</p>
			<pre><code class="language-lua">int object.lastDriverTime
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			maxHealth
		</summary>
		<div style="margin-left:16px;">
			<p>max health as it can be altered</p>
			<pre><code class="language-lua">int object.maxHealth
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			modelHash
		</summary>
		<div style="margin-left:16px;">
			<p>vehicle model index</p>
			<pre><code class="language-lua">int object.modelHash
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			needsToBeHotwired
		</summary>
		<div style="margin-left:16px;">
			<p>does the car need to be hotwired?</p>
			<pre><code class="language-lua">bool object.needsToBeHotwired
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			popType
		</summary>
		<div style="margin-left:16px;">
			<p>population type</p>
			<pre><code class="language-lua">int object.popType
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			randomSeed
		</summary>
		<div style="margin-left:16px;">
			<p>random seed</p>
			<pre><code class="language-lua">int object.randomSeed
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			status
		</summary>
		<div style="margin-left:16px;">
			<p>vehicle status flags</p>
			<pre><code class="language-lua">int object.status
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			takeOutOfParkedCarBudget
		</summary>
		<div style="margin-left:16px;">
			<p>should this vehicle be taken out of the parked car population budget?</p>
			<pre><code class="language-lua">bool object.takeOutOfParkedCarBudget
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			tyresDontBurst
		</summary>
		<div style="margin-left:16px;">
			<p>are the tyres impervious to damage?</p>
			<pre><code class="language-lua">bool object.tyresDontBurst
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			usesVerticalFlightMode
		</summary>
		<div style="margin-left:16px;">
			<p>true when it's a plane and uses special flight mode</p>
			<pre><code class="language-lua">bool object.usesVerticalFlightMode
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CVehicleGadgetDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			GadgetData
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">table<int, GadgetData> object.GadgetData
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsAttachedTrailer
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsAttachedTrailer
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NumGadgets
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.NumGadgets
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			OffsetFromParentVehicle
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">V3 object.OffsetFromParentVehicle
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CVehicleGameStateDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			AICanUseExclusiveSeats
		</summary>
		<div style="margin-left:16px;">
			<p>AI can use driver seat even if marked exclusive</p>
			<pre><code class="language-lua">bool object.AICanUseExclusiveSeats
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DontTryToEnterThisVehicleIfLockedForPlayer
		</summary>
		<div style="margin-left:16px;">
			<p>should players attempt to enter vehicle if its locked for them?</p>
			<pre><code class="language-lua">bool object.DontTryToEnterThisVehicleIfLockedForPlayer
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ExtraBrokenFlags
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.ExtraBrokenFlags
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HeadlightMultiplier
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.HeadlightMultiplier
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			OverridenVehHornHash
		</summary>
		<div style="margin-left:16px;">
			<p>Hash of a horn sound used for overriden vehicle horn</p>
			<pre><code class="language-lua">int object.OverridenVehHornHash
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			OverridingVehHorn
		</summary>
		<div style="margin-left:16px;">
			<p>Is vehicle horn has been overriden</p>
			<pre><code class="language-lua">bool object.OverridingVehHorn
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PlayerLocks
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.PlayerLocks
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RemoveAggressivelyForCarjackingMission
		</summary>
		<div style="margin-left:16px;">
			<p>Allows the vehicle to be removed aggressively during the car jacking missions</p>
			<pre><code class="language-lua">bool object.RemoveAggressivelyForCarjackingMission
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			UnFreezeWhenCleaningUp
		</summary>
		<div style="margin-left:16px;">
			<p>Vehicle flag set by script but can't be synced in script node because it would reset</p>
			<pre><code class="language-lua">bool object.UnFreezeWhenCleaningUp
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			alarmActivated
		</summary>
		<div style="margin-left:16px;">
			<p>is the alarm activated</p>
			<pre><code class="language-lua">bool object.alarmActivated
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			alarmSet
		</summary>
		<div style="margin-left:16px;">
			<p>is the alarm set?</p>
			<pre><code class="language-lua">bool object.alarmSet
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			canEjectPassengersIfLocked
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.canEjectPassengersIfLocked
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			checkForEnoughRoomToFitPed
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.checkForEnoughRoomToFitPed
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			customPathNodeStreamingRadius
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.customPathNodeStreamingRadius
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			detachedTombStone
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.detachedTombStone
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			disableSuperDummy
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.disableSuperDummy
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			doorIndividualLockedState
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">table<int, int> object.doorIndividualLockedState
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			doorIndividualLockedStateFilter
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.doorIndividualLockedStateFilter
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			doorLockState
		</summary>
		<div style="margin-left:16px;">
			<p>door lock state</p>
			<pre><code class="language-lua">int object.doorLockState
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			doorsBroken
		</summary>
		<div style="margin-left:16px;">
			<p>doors broken state</p>
			<pre><code class="language-lua">int object.doorsBroken
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			doorsNotAllowedToBeBrokenOff
		</summary>
		<div style="margin-left:16px;">
			<p>if the doors are not allowed to be broken off bitmask</p>
			<pre><code class="language-lua">int object.doorsNotAllowedToBeBrokenOff
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			doorsOpen
		</summary>
		<div style="margin-left:16px;">
			<p>doors open state</p>
			<pre><code class="language-lua">int object.doorsOpen
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			doorsOpenRatio
		</summary>
		<div style="margin-left:16px;">
			<p>doors open ratio</p>
			<pre><code class="language-lua">table<int, int> object.doorsOpenRatio
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			downforceModifierFront
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.downforceModifierFront
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			downforceModifierRear
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.downforceModifierRear
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			driftTyres
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.driftTyres
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			engineOn
		</summary>
		<div style="margin-left:16px;">
			<p>is this vehicle's engine currently on?</p>
			<pre><code class="language-lua">bool object.engineOn
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			engineSkipEngineStartup
		</summary>
		<div style="margin-left:16px;">
			<p>if the audio for the engine startup should be skipped</p>
			<pre><code class="language-lua">bool object.engineSkipEngineStartup
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			engineStarting
		</summary>
		<div style="margin-left:16px;">
			<p>is the engine starting</p>
			<pre><code class="language-lua">bool object.engineStarting
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			exclusiveDriverPedID
		</summary>
		<div style="margin-left:16px;">
			<p>exclusive driver (only peds that can drive this vehicle).</p>
			<pre><code class="language-lua">table<int, int> object.exclusiveDriverPedID
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			flaggedForCleanup
		</summary>
		<div style="margin-left:16px;">
			<p>flagged for cleanup</p>
			<pre><code class="language-lua">bool object.flaggedForCleanup
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			forceOtherVehsToStop
		</summary>
		<div style="margin-left:16px;">
			<p>should other vehicles be forced to stop for this one</p>
			<pre><code class="language-lua">bool object.forceOtherVehsToStop
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			fullThrottleActive
		</summary>
		<div style="margin-left:16px;">
			<p>Is the Full Throttle effect being applied to this vehicle</p>
			<pre><code class="language-lua">bool object.fullThrottleActive
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			fullThrottleEndTime
		</summary>
		<div style="margin-left:16px;">
			<p>Network time that Full Throttle will end</p>
			<pre><code class="language-lua">int object.fullThrottleEndTime
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ghost
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.ghost
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			handBrakeOn
		</summary>
		<div style="margin-left:16px;">
			<p>indicates whether the hand brake is on</p>
			<pre><code class="language-lua">bool object.handBrakeOn
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			hasBeenOwnedByPlayer
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.hasBeenOwnedByPlayer
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			hasLastDriver
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.hasLastDriver
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			hasTimedExplosion
		</summary>
		<div style="margin-left:16px;">
			<p>is there a timed explosive on this vehicle</p>
			<pre><code class="language-lua">bool object.hasTimedExplosion
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			headlightsFullBeamOn
		</summary>
		<div style="margin-left:16px;">
			<p>headlights full beam on</p>
			<pre><code class="language-lua">bool object.headlightsFullBeamOn
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			influenceWantedLevel
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.influenceWantedLevel
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isDriveable
		</summary>
		<div style="margin-left:16px;">
			<p>is this vehicle drivable?</p>
			<pre><code class="language-lua">bool object.isDriveable
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isParked
		</summary>
		<div style="margin-left:16px;">
			<p>is this a parked car</p>
			<pre><code class="language-lua">bool object.isParked
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isStationary
		</summary>
		<div style="margin-left:16px;">
			<p>is this a stationary car</p>
			<pre><code class="language-lua">bool object.isStationary
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isTrailerAttachmentEnabled
		</summary>
		<div style="margin-left:16px;">
			<p>Script can disable trailers from attaching themselves</p>
			<pre><code class="language-lua">bool object.isTrailerAttachmentEnabled
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			junctionArrivalTime
		</summary>
		<div style="margin-left:16px;">
			<p>Time that the vehicle arrived at its current junction</p>
			<pre><code class="language-lua">int object.junctionArrivalTime
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			junctionCommand
		</summary>
		<div style="margin-left:16px;">
			<p>Traffic flow command (stop, go)</p>
			<pre><code class="language-lua">int object.junctionCommand
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			lastDriverPedID
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.lastDriverPedID
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			lightsOn
		</summary>
		<div style="margin-left:16px;">
			<p>lights on</p>
			<pre><code class="language-lua">bool object.lightsOn
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			mercVeh
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.mercVeh
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			moveAwayFromPlayer
		</summary>
		<div style="margin-left:16px;">
			<p>should this veh move away from the player</p>
			<pre><code class="language-lua">bool object.moveAwayFromPlayer
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			noDamageFromExplosionsOwnedByDriver
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.noDamageFromExplosionsOwnedByDriver
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			overridelights
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.overridelights
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			placeOnRoadQueued
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.placeOnRoadQueued
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			planeResistToExplosion
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.planeResistToExplosion
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			pretendOccupants
		</summary>
		<div style="margin-left:16px;">
			<p>does this vehicle have pretend occupants</p>
			<pre><code class="language-lua">bool object.pretendOccupants
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			radioStation
		</summary>
		<div style="margin-left:16px;">
			<p>current radio station</p>
			<pre><code class="language-lua">int object.radioStation
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			radioStationChangedByDriver
		</summary>
		<div style="margin-left:16px;">
			<p>driver changed current radio station</p>
			<pre><code class="language-lua">bool object.radioStationChangedByDriver
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			removeWithEmptyCopOrWreckedVehs
		</summary>
		<div style="margin-left:16px;">
			<p>consider this veh with cop/wrecked vehs for removal purposes</p>
			<pre><code class="language-lua">bool object.removeWithEmptyCopOrWreckedVehs
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			roofLowered
		</summary>
		<div style="margin-left:16px;">
			<p>set when a convertible has the roof open</p>
			<pre><code class="language-lua">bool object.roofLowered
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			runningRespotTimer
		</summary>
		<div style="margin-left:16px;">
			<p>is this vehicle running the car respot timer</p>
			<pre><code class="language-lua">bool object.runningRespotTimer
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			scriptSetHandbrakeOn
		</summary>
		<div style="margin-left:16px;">
			<p>indicates whether script has specified the handbrake is on this vehicle (included in vehicle game state to ensure goes with handbrake state)</p>
			<pre><code class="language-lua">bool object.scriptSetHandbrakeOn
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			sirenOn
		</summary>
		<div style="margin-left:16px;">
			<p>is this vehicle's siren currently on?</p>
			<pre><code class="language-lua">bool object.sirenOn
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			timedExplosionCulprit
		</summary>
		<div style="margin-left:16px;">
			<p>entity responsible for the timed explosion</p>
			<pre><code class="language-lua">int object.timedExplosionCulprit
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			timedExplosionTime
		</summary>
		<div style="margin-left:16px;">
			<p>network time at which the timed explosion is to occur</p>
			<pre><code class="language-lua">int object.timedExplosionTime
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			usePlayerLightSettings
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.usePlayerLightSettings
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			useRespotEffect
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.useRespotEffect
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			vehicleOccupantsTakeExplosiveDamage
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.vehicleOccupantsTakeExplosiveDamage
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			windowsDown
		</summary>
		<div style="margin-left:16px;">
			<p>windows down state</p>
			<pre><code class="language-lua">int object.windowsDown
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			xenonLightColor
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.xenonLightColor
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CVehicleHealthDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			bodyhealth
		</summary>
		<div style="margin-left:16px;">
			<p>body health</p>
			<pre><code class="language-lua">int object.bodyhealth
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			extinguishedFireCount
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.extinguishedFireCount
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			fixedCount
		</summary>
		<div style="margin-left:16px;">
			<p>counter that is sync'd to trigger remote fix of vehicle when local fix of vehicle happens</p>
			<pre><code class="language-lua">int object.fixedCount
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			hasDamageEntity
		</summary>
		<div style="margin-left:16px;">
			<p>has this vehicle been damaged by another entity?</p>
			<pre><code class="language-lua">bool object.hasDamageEntity
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			hasMaxHealth
		</summary>
		<div style="margin-left:16px;">
			<p>health is max</p>
			<pre><code class="language-lua">bool object.hasMaxHealth
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			health
		</summary>
		<div style="margin-left:16px;">
			<p>health</p>
			<pre><code class="language-lua">int object.health
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			healthsame
		</summary>
		<div style="margin-left:16px;">
			<p>if the health is the same as body health</p>
			<pre><code class="language-lua">bool object.healthsame
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isBlownUp
		</summary>
		<div style="margin-left:16px;">
			<p>was the vehicle wrecked by explosion?</p>
			<pre><code class="language-lua">bool object.isBlownUp
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isWrecked
		</summary>
		<div style="margin-left:16px;">
			<p>is this vehicle wrecked?</p>
			<pre><code class="language-lua">bool object.isWrecked
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			lastDamagedMaterialId
		</summary>
		<div style="margin-left:16px;">
			<p>last material id that was damaged for vehicle</p>
			<pre><code class="language-lua">int object.lastDamagedMaterialId
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			numWheels
		</summary>
		<div style="margin-left:16px;">
			<p>number of wheels on this car</p>
			<pre><code class="language-lua">int object.numWheels
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			packedEngineHealth
		</summary>
		<div style="margin-left:16px;">
			<p>packed engine health value</p>
			<pre><code class="language-lua">int object.packedEngineHealth
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			packedPetrolTankHealth
		</summary>
		<div style="margin-left:16px;">
			<p>packed petrol tank health value</p>
			<pre><code class="language-lua">int object.packedPetrolTankHealth
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			suspensionHealth
		</summary>
		<div style="margin-left:16px;">
			<p>the health of the suspension for the wheels</p>
			<pre><code class="language-lua">table<int, number> object.suspensionHealth
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			suspensionHealthDefault
		</summary>
		<div style="margin-left:16px;">
			<p>is the suspension health for all wheels at the default</p>
			<pre><code class="language-lua">bool object.suspensionHealthDefault
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			tyreBrokenOff
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">table<int, bool> object.tyreBrokenOff
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			tyreDamaged
		</summary>
		<div style="margin-left:16px;">
			<p>indicates which tyres are damaged</p>
			<pre><code class="language-lua">table<int, bool> object.tyreDamaged
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			tyreDestroyed
		</summary>
		<div style="margin-left:16px;">
			<p>indicates which tyres are destroyed</p>
			<pre><code class="language-lua">table<int, bool> object.tyreDestroyed
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			tyreFire
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">table<int, bool> object.tyreFire
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			tyreHealthDefault
		</summary>
		<div style="margin-left:16px;">
			<p>is the tyre health for all wheels at the default</p>
			<pre><code class="language-lua">bool object.tyreHealthDefault
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			tyreWearRate
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">table<int, number> object.tyreWearRate
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			weaponDamageEntity
		</summary>
		<div style="margin-left:16px;">
			<p>weapon damage entity (only for script objects???????????????)</p>
			<pre><code class="language-lua">int object.weaponDamageEntity
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			weaponDamageHash
		</summary>
		<div style="margin-left:16px;">
			<p>weapon damage Hash</p>
			<pre><code class="language-lua">int object.weaponDamageHash
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CVehicleModelInfo
	</summary>
	<details style="margin-left:16px;">
		<summary>
			FromAddress
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">CVehicleModelInfo CVehicleModelInfo.FromAddress(int address)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			FromBaseModelInfo
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">CVehicleModelInfo CVehicleModelInfo.FromBaseModelInfo(CModelInfo base)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetAddress
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object:GetAddress()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsBicycle
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsBicycle()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsBike
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsBike()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsBlimp
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsBlimp()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsBoat
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsBoat()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsCar
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsCar()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsHeli
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsHeli()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsJetski
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsJetski()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsPlane
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsPlane()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsQuadbike
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsQuadbike()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsSubmarine
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsSubmarine()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsSubmarineCar
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsSubmarineCar()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsTrailer
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsTrailer()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsTrain
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsTrain()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsnAmphibiousCar
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsAmphibiousCar()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsnAmphibiousQuadbike
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsAmphibiousQuadbike()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Model
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.Model
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ModelIndex
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.ModelIndex
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CVehicleProximityMigrationDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			PopType
		</summary>
		<div style="margin-left:16px;">
			<p>population type 0x00F8</p>
			<pre><code class="language-lua">int object.PopType
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RespotCounter
		</summary>
		<div style="margin-left:16px;">
			<p>remaining time from respotting 0x0130</p>
			<pre><code class="language-lua">int object.RespotCounter
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SpeedMultiplier
		</summary>
		<div style="margin-left:16px;">
			<p>speed multiplier (used when calculating cruise speeds) 0x012C</p>
			<pre><code class="language-lua">number object.SpeedMultiplier
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			hasOccupant
		</summary>
		<div style="margin-left:16px;">
			<p>does this vehicle have passengers? 0x00C4</p>
			<pre><code class="language-lua">table<int, bool> object.hasOccupant
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			hasPopType
		</summary>
		<div style="margin-left:16px;">
			<p>has a population type 0x00F4</p>
			<pre><code class="language-lua">bool object.hasPopType
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			hasTaskData
		</summary>
		<div style="margin-left:16px;">
			<p>does the vehicle have any task data to sync 0x0132</p>
			<pre><code class="language-lua">bool object.hasTaskData
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isMoving
		</summary>
		<div style="margin-left:16px;">
			<p>is the vehicle moving (if not pos and vel not sent) 0x0104</p>
			<pre><code class="language-lua">bool object.isMoving
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			lastDriverTime
		</summary>
		<div style="margin-left:16px;">
			<p>the last time this vehicle had a driver 0x0100</p>
			<pre><code class="language-lua">int object.lastDriverTime
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			maxOccupants
		</summary>
		<div style="margin-left:16px;">
			<p>maximum number of passengers for this vehicle 0x00C0</p>
			<pre><code class="language-lua">int object.maxOccupants
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			occupantID
		</summary>
		<div style="margin-left:16px;">
			<p>IDs of the passengers 0x00D4</p>
			<pre><code class="language-lua">table<int, int> object.occupantID
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			packedVelocityX
		</summary>
		<div style="margin-left:16px;">
			<p>current velocity X (packed) 0x120</p>
			<pre><code class="language-lua">int object.packedVelocityX
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			packedVelocityY
		</summary>
		<div style="margin-left:16px;">
			<p>current velocity Y (packed) 0x124</p>
			<pre><code class="language-lua">int object.packedVelocityY
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			packedVelocityZ
		</summary>
		<div style="margin-left:16px;">
			<p>current velocity Z (packed) 0x128</p>
			<pre><code class="language-lua">int object.packedVelocityZ
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			position
		</summary>
		<div style="margin-left:16px;">
			<p>current vehicle position 0x110</p>
			<pre><code class="language-lua">V3 object.position
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			status
		</summary>
		<div style="margin-left:16px;">
			<p>vehicle status flags 0x00FC</p>
			<pre><code class="language-lua">int object.status
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			taskMigrationData
		</summary>
		<div style="margin-left:16px;">
			<p>the migration data of the current AI task 0x013C</p>
			<pre><code class="language-lua">table<int, int> object.taskMigrationData
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			taskMigrationDataSize
		</summary>
		<div style="margin-left:16px;">
			<p>the size of the migration data for the current AI task 0x0138</p>
			<pre><code class="language-lua">int object.taskMigrationDataSize
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			taskType
		</summary>
		<div style="margin-left:16px;">
			<p>the current AI task type 0x0134</p>
			<pre><code class="language-lua">int object.taskType
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CVehicleScriptGameStateDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			AllowSpecialFlightMode
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.AllowSpecialFlightMode
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BombAmmoCount
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.BombAmmoCount
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BuoyancyForceMultiplier
		</summary>
		<div style="margin-left:16px;">
			<p>shows us how much the boat wants to float back up. 0 when the boat is sinking the fastest.</p>
			<pre><code class="language-lua">number object.BuoyancyForceMultiplier
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CanEngineMissFire
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.CanEngineMissFire
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CollisionWithMapDamageScale
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.CollisionWithMapDamageScale
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CountermeasureAmmoCount
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.CountermeasureAmmoCount
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DamageThreshold
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.DamageThreshold
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DisableBreaking
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.DisableBreaking
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DisableHoverModeFlight
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.DisableHoverModeFlight
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DisableVericalFlightModeTransition
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.DisableVericalFlightModeTransition
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ExtraBoundAttachAllowance
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.ExtraBoundAttachAllowance
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GarageInstanceIndex
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.GarageInstanceIndex
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HasOutriggerDeployed
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.HasOutriggerDeployed
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HeliRopeLength
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.HeliRopeLength
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			InSubmarineMode
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.InSubmarineMode
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsCarParachuting
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.IsCarParachuting
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PopType
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.PopType
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RadioEnabledByScript
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.RadioEnabledByScript
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ScriptForceHd
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.ScriptForceHd
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ScriptMaxSpeed
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.ScriptMaxSpeed
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SpecialFlightModeUsed
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.SpecialFlightModeUsed
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TeamLockOverrides
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.TeamLockOverrides
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TeamLocks
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.TeamLocks
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TransformInstantly
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.TransformInstantly
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			UsingAutoPilot
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.UsingAutoPilot
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			VehicleProducingSlipstream
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.VehicleProducingSlipstream
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bBlockWeaponSelection
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bBlockWeaponSelection
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bBoatIgnoreLandProbes
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bBoatIgnoreLandProbes
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bIncreaseWheelCrushDamage
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bIncreaseWheelCrushDamage
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			canPickupEntitiesThatHavePickupDisabled
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.canPickupEntitiesThatHavePickupDisabled
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			disableCollisionUponCreation
		</summary>
		<div style="margin-left:16px;">
			<p>Disable collision for 1 frame upon creation</p>
			<pre><code class="language-lua">bool object.disableCollisionUponCreation
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			disablePlayerCanStandOnTop
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.disablePlayerCanStandOnTop
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			disableRampCarImpactDamage
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.disableRampCarImpactDamage
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			fOverrideArriveDistForVehPersuitAttack
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.fOverrideArriveDistForVehPersuitAttack
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			fRampImpulseScale
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.fRampImpulseScale
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			fScriptDamageScale
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.fScriptDamageScale
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			fScriptWeaponDamageScale
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.fScriptWeaponDamageScale
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			gliderState
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.gliderState
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			hasHeliRopeLengthSet
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.hasHeliRopeLengthSet
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			hasParachuteObject
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.hasParachuteObject
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			homingCanLockOnToObjects
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.homingCanLockOnToObjects
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isBeastVehicle
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.isBeastVehicle
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isinair
		</summary>
		<div style="margin-left:16px;">
			<p>is the vehicle in the air</p>
			<pre><code class="language-lua">bool object.isinair
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			lockedToXY
		</summary>
		<div style="margin-left:16px;">
			<p>is this amphibious locked in the XY plane (anchored)</p>
			<pre><code class="language-lua">bool object.lockedToXY
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			parachuteObjectId
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.parachuteObjectId
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			parachuteStickX
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.parachuteStickX
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			parachuteStickY
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.parachuteStickY
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			restrictedAmmoCount
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">table<int, int> object.restrictedAmmoCount
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			rocketBoostRechargeRate
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number object.rocketBoostRechargeRate
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			tuckInWheelsForQuadBike
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.tuckInWheelsForQuadBike
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			vehicleParachuteTintIndex
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.vehicleParachuteTintIndex
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		CVehicleTaskDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			taskData
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">table<int, int> object.taskData
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			taskDataSize
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.taskDataSize
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			taskType
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.taskType
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		Cherax
	</summary>
	<details style="margin-left:16px;">
		<summary>
			GetBuild
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int Cherax.GetBuild()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetUID
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int Cherax.GetUID()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetVersion
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">string Cherax.GetVersion()
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		ClickGUI
	</summary>
	<details style="margin-left:16px;">
		<summary>
			AddPlayerTab
		</summary>
		<div style="margin-left:16px;">
			<p>Adds a lua tab to the player options.</p>
			<pre><code class="language-lua">void ClickGUI.AddPlayerTab(string title, function() renderFunc)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AddTab
		</summary>
		<div style="margin-left:16px;">
			<p>Adds a lua tab to the main gui.</p>
			<pre><code class="language-lua">void ClickGUI.AddTab(string title, function() renderFunc)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BeginCustomChildWindow
		</summary>
		<div style="margin-left:16px;">
			<p>Begin custom ImgGui Child window.</p>
			<pre><code class="language-lua">bool ClickGUI.BeginCustomChildWindow(string label, int frames = -1, int textLines = -1)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			EndCustomChildWindow
		</summary>
		<div style="margin-left:16px;">
			<p>End custom ImgGui Child window.</p>
			<pre><code class="language-lua">void ClickGUI.EndCustomChildWindow()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetActiveMenuTab
		</summary>
		<div style="margin-left:16px;">
			<p>Get the current open menu tab.</p>
			<pre><code class="language-lua">ClickTab ClickGUI.GetActiveMenuTab()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetPos
		</summary>
		<div style="margin-left:16px;">
			<p>Get the current position in screen coordinates.</p>
			<pre><code class="language-lua">number x,y ClickGUI.GetPos()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetSize
		</summary>
		<div style="margin-left:16px;">
			<p>Get the current size in screen coordinates.</p>
			<pre><code class="language-lua">number x,y ClickGUI.GetSize()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LoadTheme
		</summary>
		<div style="margin-left:16px;">
			<p>Loads a Theme by its name.</p>
			<pre><code class="language-lua">bool ClickGUI.LoadTheme(string fileName)
ClickGUI.LoadTheme("Default")
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RemovePlayerTab
		</summary>
		<div style="margin-left:16px;">
			<p>Removes a lua tab from the player options.</p>
			<pre><code class="language-lua">void ClickGUI.RemovePlayerTab(string title)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RemoveTab
		</summary>
		<div style="margin-left:16px;">
			<p>Removes a lua tab from the main gui.</p>
			<pre><code class="language-lua">void ClickGUI.RemoveTab(string title)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RenderCustomTitleBar
		</summary>
		<div style="margin-left:16px;">
			<p>Renders a custom title bar.</p>
			<pre><code class="language-lua">void ClickGUI.RenderCustomTitleBar(string title)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RenderFeature
		</summary>
		<div style="margin-left:16px;">
			<p>Render a feature for the given feature hash and index.</p>
			<pre><code class="language-lua">bool ClickGUI.RenderFeature(int hash)
bool ClickGUI.RenderFeature(int hash, int index)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetActiveMenuTab
		</summary>
		<div style="margin-left:16px;">
			<p>Set the current open menu tab.</p>
			<pre><code class="language-lua">void ClickGUI.SetActiveMenuTab(ClickTab tab)
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		ClickTab
	</summary>
	<details style="margin-left:16px;">
		<summary>
			LuaEditor
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LuaTab
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Miscellaneous
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NumTabs
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Player
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PlayerList
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Protections
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Recovery
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SCAPI
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Session
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Settings
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Spawner
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Vehicle
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Weapon
		</summary>
	</details>

</details>
<details>
	<summary>
		Curl
	</summary>
	<details style="margin-left:16px;">
		<summary>
			AddHeader
		</summary>
		<div style="margin-left:16px;">
			<p>Adds the defined header.</p>
			<pre><code class="language-lua">LuaCurl object:AddHeader(string header)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Easy
		</summary>
		<div style="margin-left:16px;">
			<p>Create a new curl object. Never lose this object until you are completely done with it. Never do 'Curl.Easy():Setopt' because this will cause the object to be lost by lua gc.</p>
			<pre><code class="language-lua">LuaCurl Curl.Easy()
curlObject = Curl.Easy()
curlObject:Setopt(eCurlOption.CURLOPT_URL, "https://www.google.com/"):Perform()
--Peform is an async task so keep the curlObject somewhere where it does not get freed from lua gc.
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetFinished
		</summary>
		<div style="margin-left:16px;">
			<p>Get whether or not the Perform call has finished.</p>
			<pre><code class="language-lua">bool object:GetFinished()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetResponse
		</summary>
		<div style="margin-left:16px;">
			<p>Get the response. The response string is only valid when no custom Write Function was used.</p>
			<pre><code class="language-lua">eCurlCode,string object:GetResponse()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Perform
		</summary>
		<div style="margin-left:16px;">
			<p>Perform the curl operation after set up. Perform is called asynchronously. Call GetFinished() to check the current state.</p>
			<pre><code class="language-lua">void object:Perform()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Setopt
		</summary>
		<div style="margin-left:16px;">
			<p>Set specific curl options during initialize.</p>
			<pre><code class="language-lua">LuaCurl object:Setopt(eCurlOption option, string str)
LuaCurl object:Setopt(eCurlOption option, int value)
LuaCurl object:Setopt(eCurlOption.CURLOPT_URL, "https://www.google.com/")
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		D3D11SRV
	</summary>

</details>
<details>
	<summary>
		D3D11Texture
	</summary>
	<details style="margin-left:16px;">
		<summary>
			GetCurrent
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">D3D11SRV object:GetCurrent()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetFrame
		</summary>
		<div style="margin-left:16px;">
			<p>The index starts at 0. The max index is (GetFrameCount - 1).</p>
			<pre><code class="language-lua">D3D11SRV object:GetFrame(int index)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetFrameCount
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the number of frames in this texture.</p>
			<pre><code class="language-lua">int object:GetFrameCount()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetHeight
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the height this texture.</p>
			<pre><code class="language-lua">int object:GetHeight()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetWidth
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the width this texture.</p>
			<pre><code class="language-lua">int object:GetWidth()
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		DatBitBuffer
	</summary>
	<details style="margin-left:16px;">
		<summary>
			ReadBool
		</summary>
		<div style="margin-left:16px;">
			<p>Reads a bool from the buffer. Format: [value, success]</p>
			<pre><code class="language-lua">bool,bool object:ReadBool()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ReadInt
		</summary>
		<div style="margin-left:16px;">
			<p>Reads a signed integer from the buffer. Format: [value, success]</p>
			<pre><code class="language-lua">int,bool object:ReadInt(int numBits)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ReadString
		</summary>
		<div style="margin-left:16px;">
			<p>Reads a zero-terminated string from the buffer. Format: [value, success]</p>
			<pre><code class="language-lua">string,bool object:ReadString(int maxChars)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ReadUns
		</summary>
		<div style="margin-left:16px;">
			<p>Reads an unsigned integer from the buffer. Format: [value, success]</p>
			<pre><code class="language-lua">int,bool object:ReadUns(int numBits)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Seek
		</summary>
		<div style="margin-left:16px;">
			<p>Sets the bit position of the cursor. This is the location of the next read/write.</p>
			<pre><code class="language-lua">bool object:SetCursorPos(int pos)
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		EventMgr
	</summary>
	<details style="margin-left:16px;">
		<summary>
			RegisterHandler
		</summary>
		<div style="margin-left:16px;">
			<p>Register a handler that will be called for a specific event.</p>
			<pre><code class="language-lua">int EventMgr.RegisterHandler(eLuaEvent event, function func() end)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RemoveHandler
		</summary>
		<div style="margin-left:16px;">
			<p>Remove a previously registered handler by id.</p>
			<pre><code class="language-lua">void EventMgr.RemoveHandler(int id)
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		Feature
	</summary>
	<details style="margin-left:16px;">
		<summary>
			AddHotKey
		</summary>
		<div style="margin-left:16px;">
			<p>Adds a hotkey for the feature and returns itself.</p>
			<pre><code class="language-lua">Feature object:AddHotKey(int keyCode)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AddInfoContentFeature
		</summary>
		<div style="margin-left:16px;">
			<p>Add an feature as info content for eFeatureType ListWithInfo.</p>
			<pre><code class="language-lua">Feature object:AddInfoContentFeature(int hash)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AddRenderAfter
		</summary>
		<div style="margin-left:16px;">
			<p>Adds a feature to a list that will be rendered after this feature.</p>
			<pre><code class="language-lua">void object:AddRenderAfter(Feature feature)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AddRenderBefore
		</summary>
		<div style="margin-left:16px;">
			<p>Adds a feature to a list that will be rendered before this feature.</p>
			<pre><code class="language-lua">void object:AddRenderBefore(Feature feature)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ClearHotkeys
		</summary>
		<div style="margin-left:16px;">
			<p>Removes all hotkeys for this feature.</p>
			<pre><code class="language-lua">Feature object:ClearHotkeys()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ClearRenderAfter
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void object:ClearRenderAfter(Feature feature)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ClearRenderBefore
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void object:ClearRenderBefore(Feature feature)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Desc
		</summary>
		<div style="margin-left:16px;">
			<p>Description of the feature</p>
			<pre><code class="language-lua">string object.Desc
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetArrayIndex
		</summary>
		<div style="margin-left:16px;">
			<p>If this feature is part of an feature array, this is the index.</p>
			<pre><code class="language-lua">int object:GetArrayIndex()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetBoolValue
		</summary>
		<div style="margin-left:16px;">
			<p>Gets the current boolean value.</p>
			<pre><code class="language-lua">bool object:GetBoolValue()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetColor
		</summary>
		<div style="margin-left:16px;">
			<p>Gets the current color in rgba.</p>
			<pre><code class="language-lua">int r, g, b, a object:GetColor()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetColorFloats
		</summary>
		<div style="margin-left:16px;">
			<p>Gets the current color in rgba as floats from 0.0 to 1.0 .</p>
			<pre><code class="language-lua">number r, g, b, a object:GetColorFloats()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetColorU32
		</summary>
		<div style="margin-left:16px;">
			<p>Gets the current color in packed rgba.</p>
			<pre><code class="language-lua">int object:GetColorU32()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetDesc
		</summary>
		<div style="margin-left:16px;">
			<p>Get the description of the feature.</p>
			<pre><code class="language-lua">string object:GetDesc(bool translate = true)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetFloatLimitValues
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the minimum and maximum floating value.</p>
			<pre><code class="language-lua">number,number object:GetFloatLimitValues()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetFloatMaxValue
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the maximum floating value.</p>
			<pre><code class="language-lua">number object:GetFloatMaxValue()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetFloatMinValue
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the minimum floating value.</p>
			<pre><code class="language-lua">number object:GetFloatMinValue()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetFloatValue
		</summary>
		<div style="margin-left:16px;">
			<p>Gets the current floating value.</p>
			<pre><code class="language-lua">number object:GetFloatValue()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetHash
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object:GetHash()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetHotkeys
		</summary>
		<div style="margin-left:16px;">
			<p>Get all hotkeys for this feature.</p>
			<pre><code class="language-lua">table<int, int> object:GetHotkeys()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetId
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the feature id in creation order.</p>
			<pre><code class="language-lua">int object:GetId()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetIntLimitValues
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the minimum and maximum integer value.</p>
			<pre><code class="language-lua">int,int object:GetIntLimitValues()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetIntMaxValue
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the maximum integer value.</p>
			<pre><code class="language-lua">int object:GetIntMaxValue()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetIntMinValue
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the minimum integer value.</p>
			<pre><code class="language-lua">int object:GetIntMinValue()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetIntValue
		</summary>
		<div style="margin-left:16px;">
			<p>Gets the current integer value.</p>
			<pre><code class="language-lua">int object:GetIntValue()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetList
		</summary>
		<div style="margin-left:16px;">
			<p>Gets the list for feature types like combo.</p>
			<pre><code class="language-lua">table<int, string> object:GetList()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetListIndex
		</summary>
		<div style="margin-left:16px;">
			<p>Gets the current list index of the feature.</p>
			<pre><code class="language-lua">int object:GetListIndex()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetName
		</summary>
		<div style="margin-left:16px;">
			<p>Get the name of the feature.</p>
			<pre><code class="language-lua">string object:GetName(bool translate = true)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetPlayerIndex
		</summary>
		<div style="margin-left:16px;">
			<p>Same as GetArrayIndex but you might prefer this if you are using a player feature.</p>
			<pre><code class="language-lua">int object:GetPlayerIndex()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetRenderAfter
		</summary>
		<div style="margin-left:16px;">
			<p>Returns a list of features that will be rendered after this feature.</p>
			<pre><code class="language-lua">table<int, int> object:GetRenderAfter()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetRenderBefore
		</summary>
		<div style="margin-left:16px;">
			<p>Returns a list of features that will be rendered before this feature.</p>
			<pre><code class="language-lua">table<int, int> object:GetRenderBefore()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetStringValue
		</summary>
		<div style="margin-left:16px;">
			<p>Gets the current string value.</p>
			<pre><code class="language-lua">string object:GetStringValue()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetType
		</summary>
		<div style="margin-left:16px;">
			<p>Gets the feature type. E.g eFeatureType.Button</p>
			<pre><code class="language-lua">eFeatureType object:GetType()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsListIndexToggled
		</summary>
		<div style="margin-left:16px;">
			<p>Returns whether the list index has been toggled for types like ComboToggles.</p>
			<pre><code class="language-lua">bool object:IsListIndexToggled(int index)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsSaveable
		</summary>
		<div style="margin-left:16px;">
			<p>Returns whether the feature should be safed in settings or not..</p>
			<pre><code class="language-lua">bool object:IsSaveable()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsSearchable
		</summary>
		<div style="margin-left:16px;">
			<p>Gets whether a feature can be found by search or not.</p>
			<pre><code class="language-lua">bool object:IsSearchable()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsToggleFeature
		</summary>
		<div style="margin-left:16px;">
			<p>Returns whether the feature can be toggled or not.</p>
			<pre><code class="language-lua">bool object:IsToggleFeature()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsToggled
		</summary>
		<div style="margin-left:16px;">
			<p>Returns whether the feature is currently toggled or not.</p>
			<pre><code class="language-lua">bool object:IsToggled()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsVisible
		</summary>
		<div style="margin-left:16px;">
			<p>Returns whether the feature should be shown in the GUI or not.</p>
			<pre><code class="language-lua">bool object:IsVisible()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LoadSettings
		</summary>
		<div style="margin-left:16px;">
			<p>Load the specific settings for this feature from a file.</p>
			<pre><code class="language-lua">bool object:LoadSettings(string file)
object:LoadSettings("Default.json");
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Name
		</summary>
		<div style="margin-left:16px;">
			<p>Name of the feature</p>
			<pre><code class="language-lua">string object.Name
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			OnClick
		</summary>
		<div style="margin-left:16px;">
			<p>Triggers the callback as if it would be called from the GUI.</p>
			<pre><code class="language-lua">void object:OnClick()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			OnSettingsLoad
		</summary>
		<div style="margin-left:16px;">
			<p>Triggers the callback as if it would be called from the settings loader.</p>
			<pre><code class="language-lua">void object:OnSettingsLoad()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RegisterCallbackTrigger
		</summary>
		<div style="margin-left:16px;">
			<p>Registers Callback Trigger for the feature and returns itself.</p>
			<pre><code class="language-lua">Feature object:RegisterCallbackTrigger(eCallbackTrigger flags)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RemoveHotkey
		</summary>
		<div style="margin-left:16px;">
			<p>Remove specific hotkeys for this feature.</p>
			<pre><code class="language-lua">Feature object:RemoveHotkey(int keyCode, bool all)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RemoveRenderAfter
		</summary>
		<div style="margin-left:16px;">
			<p>Returns true when at least one feature was removed</p>
			<pre><code class="language-lua">bool object:RemoveRenderAfter(Feature feature)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RemoveRenderBefore
		</summary>
		<div style="margin-left:16px;">
			<p>Returns true when at least one feature was removed</p>
			<pre><code class="language-lua">bool object:RemoveRenderBefore(Feature feature)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Render
		</summary>
		<div style="margin-left:16px;">
			<p>Renders the feature in the current context. Return true if rendered.</p>
			<pre><code class="language-lua">bool object:Render()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Reset
		</summary>
		<div style="margin-left:16px;">
			<p>Restore the current values with the default values.</p>
			<pre><code class="language-lua">Feature object:Reset()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetBoolValue
		</summary>
		<div style="margin-left:16px;">
			<p>Sets the current boolean value.</p>
			<pre><code class="language-lua">Feature object:SetBoolValue(bool value)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetColor
		</summary>
		<div style="margin-left:16px;">
			<p>Sets the current color value.</p>
			<pre><code class="language-lua">Feature object:SetColor(int r, int g, int b, int a)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetColorFloats
		</summary>
		<div style="margin-left:16px;">
			<p>Sets the current color value.</p>
			<pre><code class="language-lua">Feature object:SetColorFloats(number r, number g, number b, number a)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetColorU32
		</summary>
		<div style="margin-left:16px;">
			<p>Sets the current color in packed rgba.</p>
			<pre><code class="language-lua">Feature object:SetColorU32(int color)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetDefaultValue
		</summary>
		<div style="margin-left:16px;">
			<p>Sets the default feature value and returns itself.</p>
			<pre><code class="language-lua">Feature object:SetDefaultValue(true):SetDefaultValue(1337)
Feature object:SetDefaultValue(3.33):SetDefaultValue("Test")
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetDesc
		</summary>
		<div style="margin-left:16px;">
			<p>Set the description of the feature.</p>
			<pre><code class="language-lua">Feature object:SetDesc(string desc)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetFastStepSize
		</summary>
		<div style="margin-left:16px;">
			<p>Sets the feature fast step size used in a slider.</p>
			<pre><code class="language-lua">Feature object:SetFastStepSize(5)
Feature object:SetFastStepSize(0.5)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetFloatValue
		</summary>
		<div style="margin-left:16px;">
			<p>Sets the current floating value.</p>
			<pre><code class="language-lua">Feature object:SetFloatValue(number value)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetIntValue
		</summary>
		<div style="margin-left:16px;">
			<p>Sets the current integer value.</p>
			<pre><code class="language-lua">Feature object:SetIntValue(int value)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetLimitValues
		</summary>
		<div style="margin-left:16px;">
			<p>Sets the feature minimum and maximum values and returns itself.</p>
			<pre><code class="language-lua">Feature object:SetLimitValues(20, 40):SetLimitValues(0.5, 2.5)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetList
		</summary>
		<div style="margin-left:16px;">
			<p>Sets the list for feature types like combo.</p>
			<pre><code class="language-lua">Feature object:SetList(table<int, string>)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetListIndex
		</summary>
		<div style="margin-left:16px;">
			<p>Sets the current list index of the feature.</p>
			<pre><code class="language-lua">Feature object:SetListIndex(int index)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetMaxValue
		</summary>
		<div style="margin-left:16px;">
			<p>Sets the feature maximum value and returns itself.</p>
			<pre><code class="language-lua">Feature object:SetMaxValue(20):SetMaxValue(20.1)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetMinValue
		</summary>
		<div style="margin-left:16px;">
			<p>Sets the feature minimum value and returns itself.</p>
			<pre><code class="language-lua">Feature object:SetMinValue(20):SetMinValue(20.1)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetName
		</summary>
		<div style="margin-left:16px;">
			<p>Set the name of the feature.</p>
			<pre><code class="language-lua">Feature object:SetName(string name)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetNoCallbackOnPress
		</summary>
		<div style="margin-left:16px;">
			<p>This disables the callback for OnClick.</p>
			<pre><code class="language-lua">Feature object:SetNoCallbackOnClick(bool disable)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetNoCallbackOnSettingsLoad
		</summary>
		<div style="margin-left:16px;">
			<p>This disables the callback for OnSettingsLoad.</p>
			<pre><code class="language-lua">Feature object:SetNoCallbackOnSettingsLoad(bool disable)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetSaveable
		</summary>
		<div style="margin-left:16px;">
			<p>Sets whether the feature should be safed in settings or not.</p>
			<pre><code class="language-lua">Feature object:SetSaveable(bool saveable)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetSearchable
		</summary>
		<div style="margin-left:16px;">
			<p>Sets whether a feature can be found by search or not.</p>
			<pre><code class="language-lua">Feature object:SetSearchable(bool searchable)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetStepSize
		</summary>
		<div style="margin-left:16px;">
			<p>Sets the feature step size used in a slider.</p>
			<pre><code class="language-lua">Feature object:SetStepSize(5)
Feature object:SetStepSize(0.5)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetStringValue
		</summary>
		<div style="margin-left:16px;">
			<p>Sets the current string value.</p>
			<pre><code class="language-lua">Feature object:SetStringValue(string value)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetValue
		</summary>
		<div style="margin-left:16px;">
			<p>Sets the current feature value and returns itself.</p>
			<pre><code class="language-lua">Feature object:SetValue(true):SetValue(1337)
Feature object:SetValue(3.33):SetValue("Test")
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetVisible
		</summary>
		<div style="margin-left:16px;">
			<p>Sets whether the feature should be shown in the GUI or not.</p>
			<pre><code class="language-lua">Feature object:SetVisible(bool visible)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Toggle
		</summary>
		<div style="margin-left:16px;">
			<p>Flips the current boolean value of this feature.</p>
			<pre><code class="language-lua">Feature object:Toggle()
Feature object:Toggle(bool on)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ToggleListIndex
		</summary>
		<div style="margin-left:16px;">
			<p>Toggles the list index for types like ComboToggles.</p>
			<pre><code class="language-lua">Feature object:ToggleListIndex(int index, bool toggle)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TriggerCallback
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void object:TriggerCallback()
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		FeatureMgr
	</summary>
	<details style="margin-left:16px;">
		<summary>
			AddFeature
		</summary>
		<div style="margin-left:16px;">
			<p>Create and add a new feature to the list.</p>
			<pre><code class="language-lua">Feature FeatureMgr.AddFeature(int hash, string name, eFeatureType type, string desc = , function(Feature) callback = 0, bool nativeThreadExecution = true, bool forceQueue = false)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AddFeatureArray
		</summary>
		<div style="margin-left:16px;">
			<p>Create and add a new features. Returns list of the created feature hashes.</p>
			<pre><code class="language-lua">table<int, int> FeatureMgr.AddFeatureArray(int size, int hash, string name, eFeatureType type, string desc = ,function(Feature) callback = 0, bool nativeThreadExecution = true, bool forceQueue = false)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AddPlayerFeature
		</summary>
		<div style="margin-left:16px;">
			<p>Creates an array of 32 features which will automatically reset when the player leaves.</p>
			<pre><code class="language-lua">table<int, int> FeatureMgr.AddPlayerFeature(int hash, string name, eFeatureType type, string desc = , function(Feature) callback = 0, bool nativeThreadExecution = true, bool forceQueue = false)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetAllFeatureHashes
		</summary>
		<div style="margin-left:16px;">
			<p>Returns all feaure hashes.</p>
			<pre><code class="language-lua">table<int, int> FeatureMgr.GetAllFeatureHashes()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetAllFeatures
		</summary>
		<div style="margin-left:16px;">
			<p>Returns all feaures.</p>
			<pre><code class="language-lua">table<int, Feature> FeatureMgr.GetAllFeatures()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetAllPlayerFeatureHashes
		</summary>
		<div style="margin-left:16px;">
			<p>Returns all player feaure hashes.</p>
			<pre><code class="language-lua">table<int, int> FeatureMgr.GetAllPlayerFeatureHashes()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetCurrentFeatureListString
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the string value of the current feature list index.</p>
			<pre><code class="language-lua">string FeatureMgr.GetCurrentFeatureListString(int hash)
string FeatureMgr.GetCurrentFeatureListString(int hash, int index)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetFeature
		</summary>
		<div style="margin-left:16px;">
			<p>Returns a feature by hash.</p>
			<pre><code class="language-lua">Feature FeatureMgr.GetFeature(int hash)
Feature FeatureMgr.GetFeature(int hash, int index)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetFeatureByName
		</summary>
		<div style="margin-left:16px;">
			<p>Returns a feature by name.</p>
			<pre><code class="language-lua">Feature FeatureMgr.GetFeatureByName(string name)
Feature FeatureMgr.GetFeatureByName(string name, int index)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetFeatureColor
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the color value of the feature.</p>
			<pre><code class="language-lua">int r, g, b, a FeatureMgr.GetFeatureColor(int hash)
int r, g, b, a FeatureMgr.GetFeatureColor(int hash, int index)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetFeatureFloat
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the float value of the feature.</p>
			<pre><code class="language-lua">number FeatureMgr.GetFeatureFloat(int hash)
number FeatureMgr.GetFeatureFloat(int hash, int index)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetFeatureInt
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the int value of the feature.</p>
			<pre><code class="language-lua">int FeatureMgr.GetFeatureInt(int hash)
int FeatureMgr.GetFeatureInt(int hash, int index)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetFeatureList
		</summary>
		<div style="margin-left:16px;">
			<p>Returns all string items of the feature list.</p>
			<pre><code class="language-lua">table<int, string> FeatureMgr.GetFeatureList(int hash)
table<int, string> FeatureMgr.GetFeatureList(int hash, int index)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetFeatureListIndex
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the current index of the feature list.</p>
			<pre><code class="language-lua">int FeatureMgr.GetFeatureListIndex(int hash)
int FeatureMgr.GetFeatureListIndex(int hash, int index)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetFeatureString
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the string value of the feature.</p>
			<pre><code class="language-lua">string FeatureMgr.GetFeatureString(int hash)
string FeatureMgr.GetFeatureString(int hash, int index)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetFocusedFeature
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the current focused(ClickGui) / selected(ListGui) feature.</p>
			<pre><code class="language-lua">Feature FeatureMgr.GetFocusedFeature()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetHoveredFeature
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the current hovered(ClickGui) / selected(ListGui) feature.</p>
			<pre><code class="language-lua">Feature FeatureMgr.GetHoveredFeature()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsFeatureEnabled
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the boolean value of the feature.</p>
			<pre><code class="language-lua">bool FeatureMgr.IsFeatureEnabled(int hash)
bool FeatureMgr.IsFeatureEnabled(int hash, int index)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsFeatureToggled
		</summary>
		<div style="margin-left:16px;">
			<p>Returns if the feature is toggled.</p>
			<pre><code class="language-lua">bool FeatureMgr.IsFeatureToggled(int hash)
bool FeatureMgr.IsFeatureToggled(int hash, int index)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LoadSettings
		</summary>
		<div style="margin-left:16px;">
			<p>Loads the given settings. File can be relative or absolute.</p>
			<pre><code class="language-lua">bool FeatureMgr.LoadSettings(string file)
FeatureMgr.LoadSettings("Default.json")
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RemoveFeature
		</summary>
		<div style="margin-left:16px;">
			<p>Removes the feature for the given hash.</p>
			<pre><code class="language-lua">bool FeatureMgr.RemoveFeature(int hash)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RemoveFeatureArray
		</summary>
		<div style="margin-left:16px;">
			<p>Removes the feature array for the given hash and size.</p>
			<pre><code class="language-lua">bool FeatureMgr.RemoveFeatureArray(int hash, int size)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RemovePlayerFeature
		</summary>
		<div style="margin-left:16px;">
			<p>Removes the player feature for the given hash.</p>
			<pre><code class="language-lua">bool FeatureMgr.RemovePlayerFeature(int hash)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ResetAllPlayerFeatures
		</summary>
		<div style="margin-left:16px;">
			<p>Resets all player features for every player.</p>
			<pre><code class="language-lua">void FeatureMgr.ResetAllPlayerFeatures()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ResetFeature
		</summary>
		<div style="margin-left:16px;">
			<p>Restore the current values with the default values of the feature.</p>
			<pre><code class="language-lua">void FeatureMgr.ResetFeature(int hash)
void FeatureMgr.ResetFeature(int hash, int index)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ResetPlayerFeatures
		</summary>
		<div style="margin-left:16px;">
			<p>Resets all player features for given player id.</p>
			<pre><code class="language-lua">void FeatureMgr.ResetPlayerFeatures(int playerIndex)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SearchFeature
		</summary>
		<div style="margin-left:16px;">
			<p>Searches the best matching features for a given result. Uses translations for results. You should cache results whenever input changes. Expensive execution time.</p>
			<pre><code class="language-lua">table<int, int> FeatureMgr.SearchFeature(string input, int maxResults, number cutoffPercent)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetFeatureColor
		</summary>
		<div style="margin-left:16px;">
			<p>Sets the color value of the feature.</p>
			<pre><code class="language-lua">void FeatureMgr.SetFeatureColor(int hash, int r, int g, int b, int a)
void FeatureMgr.SetFeatureColor(int hash, int index, int r, int g, int b, int a)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetFeatureFloat
		</summary>
		<div style="margin-left:16px;">
			<p>Sets the float value of the feature.</p>
			<pre><code class="language-lua">void FeatureMgr.SetFeatureFloat(int hash, number value)
void FeatureMgr.SetFeatureFloat(int hash, int index, number value)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetFeatureInt
		</summary>
		<div style="margin-left:16px;">
			<p>Sets the int value of the feature.</p>
			<pre><code class="language-lua">void FeatureMgr.SetFeatureInt(int hash, int value)
void FeatureMgr.SetFeatureInt(int hash, int index, int value)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetFeatureListIndex
		</summary>
		<div style="margin-left:16px;">
			<p>Sets the current index of the feature list.</p>
			<pre><code class="language-lua">void FeatureMgr.SetFeatureListIndex(int hash, int listIndex)
void FeatureMgr.SetFeatureListIndex(int hash, int index, int listIndex)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetFeatureString
		</summary>
		<div style="margin-left:16px;">
			<p>Sets the string value of the feature.</p>
			<pre><code class="language-lua">void FeatureMgr.SetFeatureString(int hash, string value)
void FeatureMgr.SetFeatureString(int hash, int index, string value)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ToggleFeature
		</summary>
		<div style="margin-left:16px;">
			<p>Flips the current boolean value of the feature.</p>
			<pre><code class="language-lua">void FeatureMgr.ToggleFeature(int hash)
void FeatureMgr.ToggleFeature(int hash, int index)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TriggerFeatureCallback
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void FeatureMgr.TriggerFeatureCallback(int hash)
void FeatureMgr.TriggerFeatureCallback(int hash, int index)
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		FileMgr
	</summary>
	<details style="margin-left:16px;">
		<summary>
			CreateDir
		</summary>
		<div style="margin-left:16px;">
			<p>Ensures that the given path is a directory.</p>
			<pre><code class="language-lua">bool FileMgr.CreateDir(string path)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DeleteFile
		</summary>
		<div style="margin-left:16px;">
			<p>Deletes the given file using an absolute path.</p>
			<pre><code class="language-lua">void FileMgr.DeleteFile(string path)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DoesFileExist
		</summary>
		<div style="margin-left:16px;">
			<p>Check whether the file exist using an absolute path.</p>
			<pre><code class="language-lua">bool FileMgr.DoesFileExist(string path)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			FindFiles
		</summary>
		<div style="margin-left:16px;">
			<p>Returns a list of all found files.</p>
			<pre><code class="language-lua">table<int,string> FileMgr.FindFiles(string path, string extension, bool recursive)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetMenuRootPath
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the root directory of the menu.</p>
			<pre><code class="language-lua">string FileMgr.GetMenuRootPath()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ReadFileContent
		</summary>
		<div style="margin-left:16px;">
			<p>Reads the file content using an absolute path.</p>
			<pre><code class="language-lua">string FileMgr.ReadFileContent(string path)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Unzip
		</summary>
		<div style="margin-left:16px;">
			<p>Extract a .zip file to a given directory.</p>
			<pre><code class="language-lua">bool FileMgr.Unzip(string zipName, string dir)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			WriteFileContent
		</summary>
		<div style="margin-left:16px;">
			<p>Writes the given content to a file using an absolute path.</p>
			<pre><code class="language-lua">bool FileMgr.WriteFileContent(string path, string content, bool append = false)
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		GTA
	</summary>
	<details style="margin-left:16px;">
		<summary>
			AddChatMessageToPool
		</summary>
		<div style="margin-left:16px;">
			<p>Adds a chat message locally on your pc only. You can specify the sender of the message. The message has a max length of 255 characters.</p>
			<pre><code class="language-lua">void GTA.AddChatMessageToPool(int playerId, string message, bool team)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BasketAddItem
		</summary>
		<div style="margin-left:16px;">
			<p>Adds an item to the Basket Transaction.</p>
			<pre><code class="language-lua">bool GTA.BasketAddItem(table<int, int>)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BasketStart
		</summary>
		<div style="margin-left:16px;">
			<p>Initializes a Basket Transaction.</p>
			<pre><code class="language-lua">bool valid, int transactionId GTA.BasketStart(int category, int action, int flags)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BeginService
		</summary>
		<div style="margin-left:16px;">
			<p>Initializes a new Service Transaction.</p>
			<pre><code class="language-lua">bool valid, int transactionId GTA.BeginService(int type, int category, int service, int action, int price, int flags)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CheckoutStart
		</summary>
		<div style="margin-left:16px;">
			<p>Starts the checkout of a transaction. Should be used for services and baskets.</p>
			<pre><code class="language-lua">bool GTA.CheckoutStart(int transactionId)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ConvertSectorToWorldPosition
		</summary>
		<div style="margin-left:16px;">
			<p>Converts the sector pos to world cords.</p>
			<pre><code class="language-lua">V3 GTA.ConvertSectorToWorldPosition(V3 sectorIn, V3 relativePos)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ConvertWorldToSectorPosition
		</summary>
		<div style="margin-left:16px;">
			<p>Converts the world pos to sector and relative position. This is being used in sync data nodes to sync the actual position of entities. </p>
			<pre><code class="language-lua">V3,V3 GTA.ConvertWorldToSectorPosition(V3 pos)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CreateObject
		</summary>
		<div style="margin-left:16px;">
			<p>Spawns an object. Should only be executed in a native thread.</p>
			<pre><code class="language-lua">int GTA.CreateObject(int hash, float x, float y, float z, bool dynamic, bool isNetworked = true)
int GTA.CreateObject(string model, float x, float y, float z, bool dynamic, bool isNetworked = true)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CreatePed
		</summary>
		<div style="margin-left:16px;">
			<p>Spawns a ped. Should only be executed in a native thread.</p>
			<pre><code class="language-lua">int GTA.CreatePed(int hash, int pedType, float x, float y, float z, number heading, bool isNetworked = true, bool autoCleanup = true)
int GTA.CreatePed(string model, int pedType, float x, float y, float z, number heading, bool isNetworked = true, bool autoCleanup = true)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CreateRandomPed
		</summary>
		<div style="margin-left:16px;">
			<p>Creates a random ped. Should only be executed in a native thread.</p>
			<pre><code class="language-lua">int GTA.CreateRandomPed(float x, float y, float z)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CreateWorldObject
		</summary>
		<div style="margin-left:16px;">
			<p>Spawns an world object using a bypass. Should only be executed in a native thread.</p>
			<pre><code class="language-lua">int GTA.CreateWorldObject(int hash, float x, float y, float z, bool dynamic, bool isNetworked = true)
int GTA.CreateWorldObject(string model, float x, float y, float z, bool dynamic, bool isNetworked = true)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DrawPedPreview
		</summary>
		<div style="margin-left:16px;">
			<p>Renders a given CPed on the frontend.</p>
			<pre><code class="language-lua">void GTA.DrawPedPreview(CPed ped, v2 relativeScreen, float distance, float pitch, float yaw, float lightning)
GTA.DrawPedPreview(pPed, v2.new(0.5, 0.5), -4.0, 0.0, 0.0, 1.0)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ForceScriptHost
		</summary>
		<div style="margin-left:16px;">
			<p>Forces yourself to script host of the given script.</p>
			<pre><code class="language-lua">void GTA.ForceScriptHost(int scriptHash)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetBonePos2D
		</summary>
		<div style="margin-left:16px;">
			<p>Does the same as GetBonePos3D and then converts them to normalized screen coordinates.</p>
			<pre><code class="language-lua">V2 GTA.GetBonePos2D(CPed ped, int wMask)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetBonePos3D
		</summary>
		<div style="margin-left:16px;">
			<p>Gets the bone world position based on the specified ped and mask.</p>
			<pre><code class="language-lua">V3 GTA.GetBonePos3D(CPed ped, int wMask)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetDisplayNameFromHash
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the display name of a specific hash.</p>
			<pre><code class="language-lua">string GTA.GetDisplayNameFromHash(int hash)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetGroundZ
		</summary>
		<div style="margin-left:16px;">
			<p>Returns whether the ground was found and the Z coordinate it was found at.</p>
			<pre><code class="language-lua">bool, number GTA.GetGroundZ(number x, number y)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetLabelText
		</summary>
		<div style="margin-left:16px;">
			<p>Returns a specific label for a given text entry.</p>
			<pre><code class="language-lua">string GTA.GetLabelText(string str)
string GTA.GetLabelText(int hashCode)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetLocalPed
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the local player CPed. Might be nil.</p>
			<pre><code class="language-lua">CPed GTA.GetLocalPed()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetLocalPlayerId
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the local player id.</p>
			<pre><code class="language-lua">int GTA.GetLocalPlayerId()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetLocalVehicle
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the local player's current CVehicle. Might be nil.</p>
			<pre><code class="language-lua">CVehicle GTA.GetLocalVehicle()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetModelInfoFromHash
		</summary>
		<div style="margin-left:16px;">
			<p>Returns Model Info by hash. Returns nil if no CBaseModelInfo found.</p>
			<pre><code class="language-lua">CBaseModelInfo GTA.GetModelInfoFromHash(int hash)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetModelInfoFromIndex
		</summary>
		<div style="margin-left:16px;">
			<p>Returns Model Info by index. Returns nil if no CBaseModelInfo found.</p>
			<pre><code class="language-lua">CBaseModelInfo GTA.GetModelInfoFromIndex(int index)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetModelInfoIndexFromHash
		</summary>
		<div style="margin-left:16px;">
			<p>Returns Model Info Index by hash. Returns -1 if invalid.</p>
			<pre><code class="language-lua">int GTA.GetModelInfoIndexFromHash(int hash)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetModelNameFromHash
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the model name of the model hash.</p>
			<pre><code class="language-lua">string GTA.GetModelNameFromHash(int hash)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GiveControl
		</summary>
		<div style="margin-left:16px;">
			<p>Force another player take control of the given entity.</p>
			<pre><code class="language-lua">void GTA.GiveControl(int playerId, int iEntity)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GiveScriptHost
		</summary>
		<div style="margin-left:16px;">
			<p>Give a sepcific player script host of the given script.</p>
			<pre><code class="language-lua">void GTA.GiveScriptHost(int playerId, int scriptHash)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HandleToPointer
		</summary>
		<div style="margin-left:16px;">
			<p>Converts an entity handle into a CPhysical pointer.</p>
			<pre><code class="language-lua">CPhysical GTA.HandleToPointer(int handle)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PointerToHandle
		</summary>
		<div style="margin-left:16px;">
			<p>Converts a CPhysical pointer into an entity handle.</p>
			<pre><code class="language-lua">int GTA.PointerToHandle(CPhysical ptr)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RegisterFile
		</summary>
		<div style="margin-left:16px;">
			<p>Registers the given file for the game so it can be used by natives.</p>
			<pre><code class="language-lua">bool GTA.RegisterFile(string path)
GTA.RegisterFile(path .. "MyAssets.ytd")
GRAPHICS.REQUEST_STREAMED_TEXTURE_DICT("MyAssets")
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RemoveLabelText
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void GTA.RemoveLabelText(string label)
GTA.RemoveLabelText("LOADING_MPLAYER_L")
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SendChatMessageToEveryone
		</summary>
		<div style="margin-left:16px;">
			<p>Sends a chat message to every player in the session. Note: You won't see that message yourself unless you manually add it to the chat pool. The message has a max length of 255 characters.</p>
			<pre><code class="language-lua">void GTA.SendChatMessageToEveryone(string message, bool team)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SendChatMessageToPlayer
		</summary>
		<div style="margin-left:16px;">
			<p>Sends a chat message to a given player in the session. Note: You won't see that message yourself unless you manually add it to the chat pool. The message has a max length of 255 characters.</p>
			<pre><code class="language-lua">void GTA.SendChatMessageToPlayer(int playerId, string message, bool team)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetLabelText
		</summary>
		<div style="margin-left:16px;">
			<p>Overwrites the text for a specifc label which is being used by the game.</p>
			<pre><code class="language-lua">void GTA.SetLabelText(string label, string text)
GTA.SetLabelText("LOADING_MPLAYER_L", "Loading GTA Online with Cherax")
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SpawnVehicle
		</summary>
		<div style="margin-left:16px;">
			<p>Should only be executed in a native thread.</p>
			<pre><code class="language-lua">int GTA.SpawnVehicle(int hash, float x, float y, float z, number heading, bool isNetworked = true, bool autoCleanup = true)
int GTA.SpawnVehicle(string model, float x, float y, float z, number heading, bool isNetworked = true, bool autoCleanup = true)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SpawnVehicleForPlayer
		</summary>
		<div style="margin-left:16px;">
			<p>Spawns a vehicle in front of the given player. Should only be executed in a native thread.</p>
			<pre><code class="language-lua">int GTA.SpawnVehicleForPlayer(int hash, int player, number forward = 5.0)
int GTA.SpawnVehicleForPlayer(string model, int player, number forward = 5.0)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TriggerScriptEvent
		</summary>
		<div style="margin-left:16px;">
			<p>Triggers a script event for given player(s).</p>
			<pre><code class="language-lua">int GTA.TriggerScriptEvent(int bitflags, table<int, int> arguments)
int GTA.TriggerScriptEvent(int bitflags, variadic_args arguments)

</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			WorldToScreen
		</summary>
		<div style="margin-left:16px;">
			<p>Converts a 3D world position to a 2D normalized screen position. To get the actual screen coordinates multiply them with the screen size.</p>
			<pre><code class="language-lua">float, float GTA.WorldToScreen(float x, y, z)

</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		GUI
	</summary>
	<details style="margin-left:16px;">
		<summary>
			AddToast
		</summary>
		<div style="margin-left:16px;">
			<p>Creates a toast notification.</p>
			<pre><code class="language-lua">bool GUI.AddToast(string title, string text, int duration, eToastPos pos)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetCurrentRenderMode
		</summary>
		<div style="margin-left:16px;">
			<p>Returns which GUI Mode is currently rendering. Usefull when Both GUIs are rendering in the same frame.</p>
			<pre><code class="language-lua">eGuiMode GUI.GetCurrentRenderMode()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetMode
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the current GUI mode.</p>
			<pre><code class="language-lua">eGuiMode GUI.GetMode()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsOpen
		</summary>
		<div style="margin-left:16px;">
			<p>Returns whether the GUI is open or not.</p>
			<pre><code class="language-lua">bool GUI.IsOpen()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetMode
		</summary>
		<div style="margin-left:16px;">
			<p>Sets the current GUI Mode</p>
			<pre><code class="language-lua">void GUI.SetMode(eGuiMode mode)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Toggle
		</summary>
		<div style="margin-left:16px;">
			<p>Toggle the GUI.</p>
			<pre><code class="language-lua">void GUI.Toggle()
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		GadgetData
	</summary>
	<details style="margin-left:16px;">
		<summary>
			Data
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">table<int, int> object.Data
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Type
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.int32_t Type
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		GamerHandle
	</summary>
	<details style="margin-left:16px;">
		<summary>
			IsValid
		</summary>
		<div style="margin-left:16px;">
			<p>Returns true if the GamerHandle is valid.</p>
			<pre><code class="language-lua">bool object:IsValid()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			New
		</summary>
		<div style="margin-left:16px;">
			<p>Create a new GamerHandle object.</p>
			<pre><code class="language-lua">GamerHandle GamerHandle()
GamerHandle GamerHandle.New(int rockstarId)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Platform
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RockstarId
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ToBuffer
		</summary>
		<div style="margin-left:16px;">
			<p>Converts the GamerHandle into a GamerHandleBuffer used by most natives.</p>
			<pre><code class="language-lua">GamerHandleBuffer object:ToBuffer()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			UNK1
		</summary>
	</details>

</details>
<details>
	<summary>
		GamerHandleBuffer
	</summary>
	<details style="margin-left:16px;">
		<summary>
			GetBuffer
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the buffer address.</p>
			<pre><code class="language-lua">int object:GetBuffer()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetSize
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the size of the GamerHandleBuffer.</p>
			<pre><code class="language-lua">int object:GetSize()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			New
		</summary>
		<div style="margin-left:16px;">
			<p>Create a new GamerHandleBuffer object.</p>
			<pre><code class="language-lua">GamerHandleBuffer GamerHandleBuffer.New()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ToHandle
		</summary>
		<div style="margin-left:16px;">
			<p>Converts the GamerHandleBuffer into a GamerHandle.</p>
			<pre><code class="language-lua">GamerHandle object:ToHandle()
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		GamerInfo
	</summary>
	<details style="margin-left:16px;">
		<summary>
			HostKey
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Name
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RockstarId
		</summary>
	</details>

</details>
<details>
	<summary>
		HotKeyMgr
	</summary>
	<details style="margin-left:16px;">
		<summary>
			AddHotkey
		</summary>
		<div style="margin-left:16px;">
			<p>Adds a new hotkey for a feature.</p>
			<pre><code class="language-lua">void HotKeyMgr.AddHotkey(int hash, int key)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetAllHotkeys
		</summary>
		<div style="margin-left:16px;">
			<p>Returns all hotkeys and their associated feature hash.</p>
			<pre><code class="language-lua">table<int, table<int, int>> HotKeyMgr.GetAllHotkeys()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetHotKeys
		</summary>
		<div style="margin-left:16px;">
			<p>Returns all hotkeys for a specific feature hash.</p>
			<pre><code class="language-lua"> table<int, int> HotKeyMgr.GetHotKeys(int hash)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RemoveHotkey
		</summary>
		<div style="margin-left:16px;">
			<p>Removes specific hotkey from an feature.</p>
			<pre><code class="language-lua"> void HotKeyMgr.RemoveHotkey(int hash, int key)
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		ImGui
	</summary>
	<details style="margin-left:16px;">
		<summary>
			AddCircle
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void ImGui.AddCircle(number x, number y, number radius, int r, int g, int b, int a, int numSegments = 0, number thickness = 1.0)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AddCircleFilled
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void ImGui.AddCircleFilled(number x, number y, number radius, int r, int g, int b, int a, int numSegments = 0)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AddImage
		</summary>
		<div style="margin-left:16px;">
			<p>min and max represent the upper-left and lower-right corners of the rectangle.
uv_min and uv_max represent the normalized texture coordinates to use for those corners. Using (0,0)->(1,1) texture coordinates will generally display the entire texture.</p>
			<pre><code class="language-lua">void ImGui.AddImage(D3D11SRV texture, number min_x, number min_y, number max_x, number max_y, number uv_min_x = 0.0, number uv_min_y = 0.0, number uv_max_x = 1.0, number uv_max_y = 1.0, int color = 255 << 24 | 255 << 16 | 255 << 8 | 255)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AddImageQuad
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void ImGui.AddImageQuad(D3D11SRV texture, V2 p1, V2 p2, V2 p3, V2 p4, V2 uv1 = Vector2.New(0.0, 0.0), V2 uv2 = Vector2.New(1.0, 0.0), V2 uv3 = Vector2.New(1.0, 1.0), V2 uv4 = Vector2.New(0.0, 1.0), int alpha = 255)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AddImageRotated
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void ImGui.AddImageRotated(D3D11SRV texture, number center_x, number center_y, number width, number height, number angle, int alpha = 255)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AddImageRounded
		</summary>
		<div style="margin-left:16px;">
			<p>Same as AddImage with rounding.</p>
			<pre><code class="language-lua">void ImGui.AddImageRounded(D3D11SRV texture, number min_x, number min_y, number max_x, number max_y, number uv_min_x = 0.0, number uv_min_y = 0.0, number uv_max_x = 1.0, number uv_max_y = 1.0, int color = 255 << 24 | 255 << 16 | 255 << 8 | 255, number rounding = 16.0)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AddLine
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void ImGui.AddLine(number x1, number y1, number x2, number y2, int r, int g, int b, int a, number thickness = 1.0)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AddRect
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void ImGui.AddRect(number x1, number y1, number x2, number y2, int r, int g, int b, int a, number rounding = 1.0, int drawFlags = 0, number thickness = 1.0)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AddRectFilled
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void ImGui.AddRectFilled(number x1, number y1, number x2, number y2, int r, int g, int b, int a, number rounding = 1.0, int drawFlags = 0)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AddRectFilledMultiColor
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void ImGui.AddRectFilled(number x1, number y1, number x2, number y2, int col_upr_left, int col_upr_right, int col_bot_right, int col_bot_left)
ImGui.AddRectFilled(0, 0, 100, 100, ColorConvertRGBAToU32({255, 255, 255, 255}), ColorConvertRGBAToU32({255, 255, 255, 255}), ColorConvertRGBAToU32({0, 0, 0, 255}), ColorConvertRGBAToU32({0, 0, 0, 255}))
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AddText
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void ImGui.AddText(number x, number y, strig text, int r, int g, int b, int a)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AddTriangle
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void ImGui.AddTriangle(number x1, number y1, number x2, number y2, number x3, number y3, int r, int g, int b, int a, number thickness = 1.0)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AddTriangleFilled
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void ImGui.AddTriangleFilled(number x1, number y1, number x2, number y2, number x3, number y3, int r, int g, int b, int a)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AlignTextToFramePadding
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ArrowButton
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Begin
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BeginChild
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BeginChildFrame
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BeginCombo
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BeginGroup
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BeginMainMenuBar
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BeginMenu
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BeginMenuBar
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BeginPopup
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BeginPopupContextItem
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BeginPopupContextVoid
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BeginPopupContextWindow
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BeginPopupModal
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BeginTabBar
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BeginTabItem
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BeginTable
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool ImGui.BeginTable(string strId, int columns, ImGuiTableFlags flags)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BeginTooltip
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BgAddCircle
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void ImGui.BgAddCircle(number x, number y, number radius, int r, int g, int b, int a, int numSegments = 0, number thickness = 1.0)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BgAddCircleFilled
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void ImGui.BgAddCircleFilled(number x, number y, number radius, int r, int g, int b, int a, int numSegments = 0)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BgAddImage
		</summary>
		<div style="margin-left:16px;">
			<p>min and max represent the upper-left and lower-right corners of the rectangle.
uv_min and uv_max represent the normalized texture coordinates to use for those corners. Using (0,0)->(1,1) texture coordinates will generally display the entire texture.</p>
			<pre><code class="language-lua">void ImGui.BgAddImage(D3D11SRV texture, number min_x, number min_y, number max_x, number max_y, number uv_min_x = 0.0, number uv_min_y = 0.0, number uv_max_x = 1.0, number uv_max_y = 1.0, int color = 255 << 24 | 255 << 16 | 255 << 8 | 255)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BgAddImageQuad
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void ImGui.BgAddImageQuad(D3D11SRV texture, V2 p1, V2 p2, V2 p3, V2 p4, V2 uv1 = Vector2.New(0.0, 0.0), V2 uv2 = Vector2.New(1.0, 0.0), V2 uv3 = Vector2.New(1.0, 1.0), V2 uv4 = Vector2.New(0.0, 1.0), int alpha = 255)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BgAddImageRotated
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void ImGui.BgAddImageRotated(D3D11SRV texture, number center_x, number center_y, number width, number height, number angle, int alpha = 255)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BgAddImageRounded
		</summary>
		<div style="margin-left:16px;">
			<p>Same as AddImage with rounding.</p>
			<pre><code class="language-lua">void ImGui.BgAddImageRounded(D3D11SRV texture, number min_x, number min_y, number max_x, number max_y, number uv_min_x = 0.0, number uv_min_y = 0.0, number uv_max_x = 1.0, number uv_max_y = 1.0, int color = 255 << 24 | 255 << 16 | 255 << 8 | 255, number rounding = 16.0)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BgAddLine
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void ImGui.BgAddLine(number x1, number y1, number x2, number y2, int r, int g, int b, int a, number thickness = 1.0)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BgAddRect
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void ImGui.BgAddRect(number x1, number y1, number x2, number y2, int r, int g, int b, int a, number rounding = 1.0, int drawFlags = 0, number thickness = 1.0)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BgAddRectFilled
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void ImGui.BgAddRectFilled(number x1, number y1, number x2, number y2, int r, int g, int b, int a, number rounding = 1.0, int drawFlags = 0)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BgAddRectFilledMultiColor
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void ImGui.AddRectFilled(number x1, number y1, number x2, number y2, int col_upr_left, int col_upr_right, int col_bot_right, int col_bot_left)
ImGui.AddRectFilled(0, 0, 100, 100, ColorConvertRGBAToU32({255, 255, 255, 255}), ColorConvertRGBAToU32({255, 255, 255, 255}), ColorConvertRGBAToU32({0, 0, 0, 255}), ColorConvertRGBAToU32({0, 0, 0, 255}))
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BgAddText
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void ImGui.BgAddText(number x, number y, strig text, int r, int g, int b, int a)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BgAddTriangle
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void ImGui.BgAddTriangle(number x1, number y1, number x2, number y2, number x3, number y3, int r, int g, int b, int a, number thickness = 1.0)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BgAddTriangleFilled
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void ImGui.AddTriangleFilled(number x1, number y1, number x2, number y2, number x3, number y3, int r, int g, int b, int a)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Bullet
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BulletText
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Button
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CalcItemWidth
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CalcTextSize
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CaptureKeyboardFromApp
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CaptureMouseFromApp
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Checkbox
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CloseCurrentPopup
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CollapsingHeader
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ColorConvertFloat4ToU32
		</summary>
		<div style="margin-left:16px;">
			<p>Converts a float 4 into a packed color.</p>
			<pre><code class="language-lua">int ImGui.ColorConvertFloat4ToU32(table<int, number> color)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ColorConvertHSVtoRGB
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ColorConvertRGBAToU32
		</summary>
		<div style="margin-left:16px;">
			<p>Converts an rgba table to a packed color.</p>
			<pre><code class="language-lua">int ImGui.ColorConvertRGBAToU32(table<int, int> rgba)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ColorConvertRGBtoHSV
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ColorConvertU32ToFloat4
		</summary>
		<div style="margin-left:16px;">
			<p>Converts a packed color into a float 4.</p>
			<pre><code class="language-lua">table<int, number> ImGui.ColorConvertU32ToFloat4(int color)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ColorEdit3
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ColorEdit4
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ColorPicker3
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ColorPicker4
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Columns
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Combo
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DragFloat
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DragFloat2
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DragFloat3
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DragFloat4
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DragInt
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DragInt2
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DragInt3
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DragInt4
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Dummy
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			End
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			EndChild
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			EndChildFrame
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			EndCombo
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			EndGroup
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			EndMainMenuBar
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			EndMenu
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			EndMenuBar
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			EndPopup
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			EndTabBar
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			EndTabItem
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			EndTable
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void ImGui.EndTable()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			EndTooltip
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetClipboardText
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetColorU32
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetColumnIndex
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetColumnOffset
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetColumnWidth
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetColumnsCount
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetContentRegionAvail
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetContentRegionMax
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetCursorPos
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetCursorPosX
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetCursorPosY
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetCursorScreenPos
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetCursorStartPos
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetDisplaySize
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number, number ImGui.GetDisplaySize()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetFont
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetFontSize
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetFontTexUvWhitePixel
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetFrameCount
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetFrameHeight
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetFrameHeightWithSpacing
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetFrameRate
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number ImGui.GetFrameRate()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetID
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetItemRectMax
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetItemRectMin
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetItemRectSize
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetKeyIndex
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetMouseCursor
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetMouseDragDelta
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetMousePos
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetMousePosOnOpeningCurrentPopup
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetScrollMaxX
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetScrollMaxY
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetScrollX
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetScrollY
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetStyleColorName
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetStyleColorVec4
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetTextLineHeight
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetTextLineHeightWithSpacing
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetTime
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetTreeNodeToLabelSpacing
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetWindowContentRegionMax
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetWindowContentRegionMin
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetWindowContentRegionWidth
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetWindowDpiScale
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetWindowHeight
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetWindowPos
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetWindowSize
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetWindowWidth
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Indent
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			InputDouble
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			InputFloat
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			InputFloat2
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			InputFloat3
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			InputFloat4
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			InputInt
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			InputInt2
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			InputInt3
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			InputInt4
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			InputText
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			InputTextMultiline
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			InputTextWithHint
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			InvisibleButton
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsAnyItemActive
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsAnyItemFocused
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsAnyItemHovered
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsAnyMouseDown
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsItemActivated
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsItemActive
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsItemClicked
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsItemDeactivated
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsItemDeactivatedAfterEdit
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsItemEdited
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsItemFocused
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsItemHovered
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsItemToggledOpen
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsItemVisible
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsKeyDown
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsKeyPressed
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsKeyReleased
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsMouseClicked
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsMouseDoubleClicked
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsMouseDown
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsMouseDragging
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsMouseHoveringRect
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsMouseReleased
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsPopupOpen
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsRectVisible
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsWindowAppearing
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsWindowCollapsed
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsWindowFocused
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsWindowHovered
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LabelText
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ListBox
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ListBoxFooter
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ListBoxHeader
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LogButtons
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LogFinish
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LogText
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LogToClipboard
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LogToFile
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LogToTTY
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			MenuItem
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NewLine
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NextColumn
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			OpenPopup
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			OpenPopupOnItemClick
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PopAllowKeyboardFocus
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PopButtonRepeat
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PopClipRect
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PopFont
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PopID
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PopItemWidth
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PopStyleColor
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PopStyleVar
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PopTextWrapPos
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ProgressBar
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PushAllowKeyboardFocus
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PushButtonRepeat
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PushClipRect
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PushFont
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PushID
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PushItemWidth
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PushStyleColor
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PushStyleVar
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PushTextWrapPos
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RadioButton
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ResetMouseDragDelta
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SameLine
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Selectable
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Separator
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetClipboardText
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetColumnOffset
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetColumnWidth
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetCursorPos
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetCursorPosX
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetCursorPosY
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetCursorScreenPos
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetItemAllowOverlap
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetItemDefaultFocus
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetKeyboardFocusHere
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetMouseCursor
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetNextItemOpen
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetNextItemWidth
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetNextWindowBgAlpha
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetNextWindowCollapsed
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetNextWindowContentSize
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetNextWindowFocus
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetNextWindowPos
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetNextWindowSize
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetNextWindowSizeConstraints
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetScrollFromPosX
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetScrollFromPosY
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetScrollHereX
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetScrollHereY
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetScrollX
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetScrollY
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetTabItemClosed
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetTooltip
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetWindowCollapsed
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetWindowFocus
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetWindowFontScale
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetWindowPos
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetWindowSize
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SliderAngle
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SliderFloat
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SliderFloat2
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SliderFloat3
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SliderFloat4
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SliderInt
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SliderInt2
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SliderInt3
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SliderInt4
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SmallButton
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Spacing
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TableNextColumn
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void ImGui.TableNextColumn()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TableNextRow
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void ImGui.TableNextRow()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TableSetColumnIndex
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool ImGui.TableSetColumnIndex(int column)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TableSetupColumn
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void ImGui.TableSetupColumn(string strId, ImGuiTableColumnFlags flags)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Text
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TextColored
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TextDisabled
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TextUnformatted
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TextWrapped
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TreeNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TreeNodeEx
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TreePop
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TreePush
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Unindent
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			VSliderFloat
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			VSliderInt
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Value
		</summary>
	</details>

</details>
<details>
	<summary>
		ImGuiCol
	</summary>
	<details style="margin-left:16px;">
		<summary>
			Border
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BorderShadow
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Button
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ButtonActive
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ButtonHovered
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			COUNT
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CheckMark
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ChildBg
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DragDropTarget
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			FrameBg
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			FrameBgActive
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			FrameBgHovered
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Header
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HeaderActive
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HeaderHovered
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			MenuBarBg
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ModalWindowDarkening
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ModalWindowDimBg
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NavHighlight
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NavWindowingDimBg
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NavWindowingHighlight
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PlotHistogram
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PlotHistogramHovered
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PlotLines
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PlotLinesHovered
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PopupBg
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ResizeGrip
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ResizeGripActive
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ResizeGripHovered
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ScrollbarBg
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ScrollbarGrab
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ScrollbarGrabActive
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ScrollbarGrabHovered
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Separator
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SeparatorActive
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SeparatorHovered
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SliderGrab
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SliderGrabActive
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Tab
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TabActive
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TabHovered
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TabUnfocused
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TabUnfocusedActive
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Text
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TextDisabled
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TextSelectedBg
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TitleBg
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TitleBgActive
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TitleBgCollapsed
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			WindowBg
		</summary>
	</details>

</details>
<details>
	<summary>
		ImGuiColorEditFlags
	</summary>
	<details style="margin-left:16px;">
		<summary>
			AlphaBar
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AlphaPreview
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AlphaPreviewHalf
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DataTypeMask_
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DefaultOptions_
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DisplayHSV
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DisplayHex
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DisplayMask_
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DisplayRGB
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Float
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HDR
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			InputHSV
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			InputMask_
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			InputRGB
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoAlpha
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoBorder
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoDragDrop
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoInputs
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoLabel
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoOptions
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoPicker
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoSidePreview
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoSmallPreview
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoTooltip
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			None
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PickerHueBar
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PickerHueWheel
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PickerMask_
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Uint8
		</summary>
	</details>

</details>
<details>
	<summary>
		ImGuiComboFlags
	</summary>
	<details style="margin-left:16px;">
		<summary>
			HeightLarge
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HeightLargest
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HeightMask
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HeightRegular
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HeightSmall
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoArrowButton
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoPreview
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			None
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PopupAlignLeft
		</summary>
	</details>

</details>
<details>
	<summary>
		ImGuiCond
	</summary>
	<details style="margin-left:16px;">
		<summary>
			Always
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Appearing
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			FirstUseEver
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			None
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Once
		</summary>
	</details>

</details>
<details>
	<summary>
		ImGuiDir
	</summary>
	<details style="margin-left:16px;">
		<summary>
			COUNT
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Down
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Left
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			None
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Right
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Up
		</summary>
	</details>

</details>
<details>
	<summary>
		ImGuiFocusedFlags
	</summary>
	<details style="margin-left:16px;">
		<summary>
			AnyWindow
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ChildWindows
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			None
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RootAndChildWindows
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RootWindow
		</summary>
	</details>

</details>
<details>
	<summary>
		ImGuiHoveredFlags
	</summary>
	<details style="margin-left:16px;">
		<summary>
			AllowWhenBlockedByActiveItem
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AllowWhenBlockedByPopup
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AllowWhenDisabled
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AllowWhenOverlapped
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AnyWindow
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ChildWindows
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			None
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RectOnly
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RootAndChildWindows
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RootWindow
		</summary>
	</details>

</details>
<details>
	<summary>
		ImGuiInputTextFlags
	</summary>
	<details style="margin-left:16px;">
		<summary>
			AllowTabInput
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AlwaysOverwrite
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AutoSelectAll
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CallbackAlways
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CallbackCharFilter
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CallbackCompletion
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CallbackEdit
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CallbackHistory
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CallbackResize
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CharsDecimal
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CharsHexadecimal
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CharsNoBlank
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CharsScientific
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CharsUppercase
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CtrlEnterForNewLine
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			EnterReturnsTrue
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			MergedItem
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Multiline
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoHorizontalScroll
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoMarkEdited
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoUndoRedo
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			None
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Password
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ReadOnly
		</summary>
	</details>

</details>
<details>
	<summary>
		ImGuiKey
	</summary>
	<details style="margin-left:16px;">
		<summary>
			A
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Backspace
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			C
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			COUNT
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Delete
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DownArrow
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			End
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Enter
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Escape
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Home
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Insert
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			KeyPadEnter
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LeftArrow
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PageDown
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PageUp
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RightArrow
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Space
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Tab
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			UpArrow
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			V
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			X
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Y
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Z
		</summary>
	</details>

</details>
<details>
	<summary>
		ImGuiMouseButton
	</summary>
	<details style="margin-left:16px;">
		<summary>
			ImGuiMouseButton_COUNT
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ImGuiMouseButton_Left
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ImGuiMouseButton_Middle
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ImGuiMouseButton_Right
		</summary>
	</details>

</details>
<details>
	<summary>
		ImGuiMouseCursor
	</summary>
	<details style="margin-left:16px;">
		<summary>
			Arrow
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			COUNT
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Hand
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			None
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NotAllowed
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ResizeAll
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ResizeEW
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ResizeNESW
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ResizeNS
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ResizeNWSE
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TextInput
		</summary>
	</details>

</details>
<details>
	<summary>
		ImGuiPopupFlags
	</summary>
	<details style="margin-left:16px;">
		<summary>
			AnyPopup
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AnyPopupId
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AnyPopupLevel
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			MouseButtonDefault_
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			MouseButtonLeft
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			MouseButtonMask_
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			MouseButtonMiddle
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			MouseButtonRight
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoOpenOverExistingPopup
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoOpenOverItems
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			None
		</summary>
	</details>

</details>
<details>
	<summary>
		ImGuiSelectableFlags
	</summary>
	<details style="margin-left:16px;">
		<summary>
			AllowDoubleClick
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AllowItemOverlap
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Disabled
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DontClosePopups
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			None
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SpanAllColumns
		</summary>
	</details>

</details>
<details>
	<summary>
		ImGuiStyleVar
	</summary>
	<details style="margin-left:16px;">
		<summary>
			Alpha
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ButtonTextAlign
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			COUNT
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CellPadding
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ChildBorderSize
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ChildRounding
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DisabledAlpha
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			FrameBorderSize
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			FramePadding
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			FrameRounding
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GrabMinSize
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GrabRounding
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IndentSpacing
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ItemInnerSpace
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ItemSpacing
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PopupBorderSize
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PopupRounding
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ScrollbarRounding
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ScrollbarSize
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SelectableTextAlign
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TabRounding
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			WindowBorderSize
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			WindowMinSize
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			WindowPadding
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			WindowRounding
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			WindowTitleAlign
		</summary>
	</details>

</details>
<details>
	<summary>
		ImGuiTabBarFlags
	</summary>
	<details style="margin-left:16px;">
		<summary>
			AutoSelectNewTabs
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			FittingPolicyDefault_
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			FittingPolicyMask_
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			FittingPolicyResizeDown
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			FittingPolicyScroll
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoCloseWithMiddleMouseButton
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoTabListScrollingButtons
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoTooltip
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			None
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Reorderable
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TabListPopupButton
		</summary>
	</details>

</details>
<details>
	<summary>
		ImGuiTabItemFlags
	</summary>
	<details style="margin-left:16px;">
		<summary>
			NoCloseWithMiddleMouseButton
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoPushId
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoTooltip
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			None
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetSelected
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			UnsavedDocument
		</summary>
	</details>

</details>
<details>
	<summary>
		ImGuiTableColumnFlags
	</summary>
	<details style="margin-left:16px;">
		<summary>
			DefaultSort
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Disabled
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IndentDisabled
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IndentEnable
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IndentMask_
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsEnabled
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsHovered
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsSorted
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsVisible
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoClip
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoDirectResize_
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoHeaderLabel
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoHeaderWidth
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoHide
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoReorder
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoResize
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoSort
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoSortAscending
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoSortDescending
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			None
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PreferSortAscending
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PreferSortDescending
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			StatusMask_
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			WidthFixed
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			WidthMask_
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			WidthStretch
		</summary>
	</details>

</details>
<details>
	<summary>
		ImGuiTableFlags
	</summary>
	<details style="margin-left:16px;">
		<summary>
			Borders
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BordersH
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BordersInner
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BordersInnerH
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BordersInnerV
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BordersOuter
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BordersOuterH
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BordersOuterV
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BordersV
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ContextMenuInBody
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Hideable
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoBordersInBody
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoBordersInBodyUntilResize
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoClip
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoHostExtendX
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoHostExtendY
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoKeepColumnsVisible
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoPadInnerX
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoPadOuterX
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoSavedSettings
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			None
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PadOuterX
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PreciseWidths
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Reorderable
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Resizable
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RowBg
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ScrollX
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ScrollY
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SizingFixedFit
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SizingFixedSame
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SizingMask_
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SizingStretchProp
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SizingStretchSame
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SortMulti
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SortTristate
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Sortable
		</summary>
	</details>

</details>
<details>
	<summary>
		ImGuiTreeNodeFlags
	</summary>
	<details style="margin-left:16px;">
		<summary>
			AllowItemOverlap
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Bullet
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CollapsingHeader
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DefaultOpen
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			FramePadding
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Framed
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Leaf
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NavLeftJumpsBackHere
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoAutoOpenOnLog
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoTreePushOnOpen
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			None
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			OpenOnArrow
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			OpenOnDoubleClick
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Selected
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SpanAvailWidth
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SpanFullWidth
		</summary>
	</details>

</details>
<details>
	<summary>
		ImGuiWindowFlags
	</summary>
	<details style="margin-left:16px;">
		<summary>
			AlwaysAutoResize
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AlwaysHorizontalScrollbar
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AlwaysUseWindowPadding
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AlwaysVerticalScrollbar
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ChildMenu
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ChildWindow
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HorizontalScrollbar
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			MenuBar
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Modal
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NavFlattened
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoBackground
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoBringToFrontOnFocus
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoCollapse
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoDecoration
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoFocusOnAppearing
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoInputs
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoMouseInputs
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoMove
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoNav
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoNavFocus
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoNavInputs
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoResize
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoSavedSettings
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoScrollWithMouse
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoScrollbar
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoTitleBar
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			None
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Popup
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Tooltip
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			UnsavedDocument
		</summary>
	</details>

</details>
<details>
	<summary>
		ListGUI
	</summary>
	<details style="margin-left:16px;">
		<summary>
			GetCurrentTab
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the top most tab.</p>
			<pre><code class="language-lua">Tab ListGUI.GetCurrentTab()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetPlayerTab
		</summary>
		<div style="margin-left:16px;">
			<p>Returns a specific player tab. (ranges from 0-31).</p>
			<pre><code class="language-lua">Tab ListGUI.GetPlayerTab(int player)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetPos
		</summary>
		<div style="margin-left:16px;">
			<p>Get the current position in screen coordinates.</p>
			<pre><code class="language-lua">number x,y ListGUI.GetPos()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetRootTab
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the root tab.</p>
			<pre><code class="language-lua">Tab ListGUI.GetRootTab()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetSize
		</summary>
		<div style="margin-left:16px;">
			<p>Get the current size in screen coordinates.</p>
			<pre><code class="language-lua">number x,y ListGUI.GetSize()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LoadTheme
		</summary>
		<div style="margin-left:16px;">
			<p>Loads a Theme by its name.</p>
			<pre><code class="language-lua">bool ListGUI.LoadTheme(string fileName)
ListGUI.LoadTheme("Default")
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RemoveTabFromStack
		</summary>
		<div style="margin-left:16px;">
			<p>Remoces the tab from the stack and jump back to the tab before.</p>
			<pre><code class="language-lua">ListGUI.RemoveTabFromStack(Tab tab)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetCurrentTab
		</summary>
		<div style="margin-left:16px;">
			<p>Adds the tab to the tab stack or jumps back if it is already in the tab stack.</p>
			<pre><code class="language-lua">ListGUI.SetCurrentTab(Tab tab)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetPos
		</summary>
		<div style="margin-left:16px;">
			<p>Set the current position in screen coordinates.</p>
			<pre><code class="language-lua">void ListGUI.SetPos(number x, number y)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetSize
		</summary>
		<div style="margin-left:16px;">
			<p>Set the current size in screen coordinates.</p>
			<pre><code class="language-lua">void ListGUI.SetSize(number x, number y)
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		ListWidget
	</summary>
	<details style="margin-left:16px;">
		<summary>
			GetDesc
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">string object:GetDesc()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetText
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">string object:GetText()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsVisible
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object:IsVisible()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetDesc
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">object:SetDesc(string desc)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetText
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">object:SetText(string text)
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		Logger
	</summary>
	<details style="margin-left:16px;">
		<summary>
			Log
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void Logger.Log(eLogColor color, string prefix, string str)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LogError
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void Logger.LogError(string str)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LogInfo
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void Logger.LogInfo(string str)
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		Memory
	</summary>
	<details style="margin-left:16px;">
		<summary>
			Alloc
		</summary>
		<div style="margin-left:16px;">
			<p>Allocates a block of size bytes of memory, returning a pointer to the beginning of the block. The content of the newly allocated block of memory is not initialized, remaining with indeterminate values. Consider using Memory.MemSet</p>
			<pre><code class="language-lua">int Memory.Alloc(int size = 24)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AllocInt
		</summary>
		<div style="margin-left:16px;">
			<p>Allocates a 4 byte buffer where an integer can be stored.</p>
			<pre><code class="language-lua">int Memory.AllocInt()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Free
		</summary>
		<div style="margin-left:16px;">
			<p>Deallocates a block of memory, making it available again for further allocations</p>
			<pre><code class="language-lua">void Memory.Free(int ptr)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetBaseAddress
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the base address of the given module.</p>
			<pre><code class="language-lua">int Memory.GetBaseAddress(string moduleName = "GTA5.exe")
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LuaCallCFunction
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void Memory.LuaCallCFunction(int addr, variadic_args arguments)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			MemSet
		</summary>
		<div style="margin-left:16px;">
			<p>Sets the first num bytes of the block of memory pointed by ptr to the specified value (interpreted as an unsigned char).</p>
			<pre><code class="language-lua">int Memory.MemSet(int ptr, int val, int num)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ReadByte
		</summary>
		<div style="margin-left:16px;">
			<p>Reads an 8-bit integer at the given address.</p>
			<pre><code class="language-lua">int Memory.ReadByte(int address)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ReadFloat
		</summary>
		<div style="margin-left:16px;">
			<p>Reads a float at the given address.</p>
			<pre><code class="language-lua">float Memory.ReadFloat(int address)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ReadInt
		</summary>
		<div style="margin-left:16px;">
			<p>Reads a 32-bit integer at the given address.</p>
			<pre><code class="language-lua">int Memory.ReadInt(int address)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ReadLong
		</summary>
		<div style="margin-left:16px;">
			<p>Reads a 64-bit integer at the given address.</p>
			<pre><code class="language-lua">int Memory.ReadLong(int address)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ReadShort
		</summary>
		<div style="margin-left:16px;">
			<p>Reads an 16-bit integer at the given address.</p>
			<pre><code class="language-lua">int Memory.ReadShort(int address)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ReadString
		</summary>
		<div style="margin-left:16px;">
			<p>Reads a string at the given address.</p>
			<pre><code class="language-lua">string Memory.ReadString(int address)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ReadUByte
		</summary>
		<div style="margin-left:16px;">
			<p>Reads an unsigned 8-bit integer at the given address.</p>
			<pre><code class="language-lua">int Memory.ReadUByte(int address)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ReadUInt
		</summary>
		<div style="margin-left:16px;">
			<p>Reads a unsigned 32-bit integer at the given address.</p>
			<pre><code class="language-lua">int Memory.ReadUInt(int address)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ReadUShort
		</summary>
		<div style="margin-left:16px;">
			<p>Reads an unsigned 16-bit integer at the given address.</p>
			<pre><code class="language-lua">int Memory.ReadUShort(int address)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ReadV3
		</summary>
		<div style="margin-left:16px;">
			<p>Reads a Vector3 at the given address.</p>
			<pre><code class="language-lua">V3 Memory.ReadV3(int address)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Rip
		</summary>
		<div style="margin-left:16px;">
			<p>Rips the given address and returns the ripped address.</p>
			<pre><code class="language-lua">int Memory.Rip(int address)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Scan
		</summary>
		<div style="margin-left:16px;">
			<p>Scans for a given pattern in a specific module and returns the address if found.</p>
			<pre><code class="language-lua">int Memory.Scan(string pattern, string moduleName = "GTA5.exe")
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			WriteByte
		</summary>
		<div style="margin-left:16px;">
			<p>Writes an 8-bit integer to the given address.</p>
			<pre><code class="language-lua">void Memory.WriteByte(int address, int value)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			WriteFloat
		</summary>
		<div style="margin-left:16px;">
			<p>Writes a float to the given address.</p>
			<pre><code class="language-lua">void Memory.WriteFloat(int address, float value)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			WriteInt
		</summary>
		<div style="margin-left:16px;">
			<p>Writes a 32-bit integer to the given address.</p>
			<pre><code class="language-lua">void Memory.WriteInt(int address, int value)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			WriteLong
		</summary>
		<div style="margin-left:16px;">
			<p>Writes a 64-bit integer to the given address.</p>
			<pre><code class="language-lua">void Memory.WriteLong(int address, int value)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			WriteShort
		</summary>
		<div style="margin-left:16px;">
			<p>Writes an 16-bit integer to the given address.</p>
			<pre><code class="language-lua">void Memory.WriteShort(int address, int value)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			WriteString
		</summary>
		<div style="margin-left:16px;">
			<p>Writes a string to the given address.</p>
			<pre><code class="language-lua">void Memory.WriteString(int address, string value)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			WriteUByte
		</summary>
		<div style="margin-left:16px;">
			<p>Writes an unsigned 8-bit integer to the given address.</p>
			<pre><code class="language-lua">void Memory.WriteUByte(int address, int value)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			WriteUInt
		</summary>
		<div style="margin-left:16px;">
			<p>Writes a unsigned 32-bit integer to the given address.</p>
			<pre><code class="language-lua">void Memory.WriteUInt(int address, int value)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			WriteUShort
		</summary>
		<div style="margin-left:16px;">
			<p>Writes an unsigned 16-bit integer to the given address.</p>
			<pre><code class="language-lua">void Memory.WriteUShort(int address, int value)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			WriteV3
		</summary>
		<div style="margin-left:16px;">
			<p>Writes a Vector3 to the given address.</p>
			<pre><code class="language-lua">void Memory.WriteV3(int address, V3 value)
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		ModderDB
	</summary>
	<details style="margin-left:16px;">
		<summary>
			AddModder
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool ModderDB.AddModder(int rockstarId, string detection)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AddModderByPlayerId
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool ModderDB.AddModderByPlayerId(int playerId, string detection)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetModderDetections
		</summary>
		<div style="margin-left:16px;">
			<p>detection format: name, count, lastTime</p>
			<pre><code class="language-lua">table<table<string, int, int>> ModderDB.GetModderDetections(int rockstarId)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetModderDetectionsByPlayerId
		</summary>
		<div style="margin-left:16px;">
			<p>detection format: name, count, lastTime</p>
			<pre><code class="language-lua">table<table<string, int, int>> ModderDB.GetModderDetectionsByPlayerId(int playerId)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RemoveModder
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool ModderDB.RemoveModder(int rockstarId, string reason)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RemoveModderDetection
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool ModderDB.RemoveModderDetection(int rockstarId, string reason)
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		Natives
	</summary>
	<details style="margin-left:16px;">
		<summary>
			InvokeBool
		</summary>
		<div style="margin-left:16px;">
			<p>Call a native that returns a boolean.</p>
			<pre><code class="language-lua">bool Natives.InvokeBool(hash, ...)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			InvokeFloat
		</summary>
		<div style="margin-left:16px;">
			<p>Call a native that returns a float.</p>
			<pre><code class="language-lua">float Natives.InvokeFloat(hash, ...)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			InvokeInt
		</summary>
		<div style="margin-left:16px;">
			<p>Call a native that returns an integer.</p>
			<pre><code class="language-lua">int Natives.InvokeInt(hash, ...)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			InvokeString
		</summary>
		<div style="margin-left:16px;">
			<p>Call a native that returns a string.</p>
			<pre><code class="language-lua">string Natives.InvokeString(hash, ...)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			InvokeV3
		</summary>
		<div style="margin-left:16px;">
			<p>Call a native that returns three floats representing a V3.</p>
			<pre><code class="language-lua">float, float, float Natives.InvokeV3(hash, ...)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			InvokeVoid
		</summary>
		<div style="margin-left:16px;">
			<p>Call a native that does not return a value.</p>
			<pre><code class="language-lua">void Natives.InvokeVoid(hash, ...)
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		NetAddress
	</summary>
	<details style="margin-left:16px;">
		<summary>
			ProxyAddr
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">SocketAddress ProxyAddr
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TargetAddr
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">SocketAddress TargetAddr
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Type
		</summary>
		<div style="margin-left:16px;">
			<p>Type of the NetAddress.</p>
			<pre><code class="language-lua">NetAddressType Type
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		NetAddressType
	</summary>
	<details style="margin-left:16px;">
		<summary>
			DIRECT
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			INVALID
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NUM_TYPES
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PEER_RELAY
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RELAY_SERVER
		</summary>
	</details>

</details>
<details>
	<summary>
		NetworkObjectMgr
	</summary>
	<details style="margin-left:16px;">
		<summary>
			ChangeOwner
		</summary>
		<div style="margin-left:16px;">
			<p>Changes the ownership of a network object.</p>
			<pre><code class="language-lua">void NetworkObjectMgr.ChangeOwner(CNetObject object, CNetGamePlayer player, int migrationType)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetNetworkObject
		</summary>
		<div style="margin-left:16px;">
			<p>includeAll - If this flag is set the function will also return unregistering objects and those being reassigned</p>
			<pre><code class="language-lua">CNetObject NetworkObjectMgr.GetNetworkObject(int netId, bool includeAll = false)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			UnregisterNetworkObject
		</summary>
		<div style="margin-left:16px;">
			<p>Unregisters a network object with the manager and removes clones on remote machines if necessary.</p>
			<pre><code class="language-lua">void NetworkObjectMgr.UnregisterNetworkObject(CNetObject object, int reason, bool bForce, bool bDestroyObject)
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		PlayerGameStateFlags
	</summary>
	<details style="margin-left:16px;">
		<summary>
			PRF_BlockRemotePlayerRecording
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool PRF_BlockRemotePlayerRecording
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PRF_UseScriptedWeaponFirePosition
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool PRF_UseScriptedWeaponFirePosition
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PlayerPreferFrontSeat
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.PlayerPreferFrontSeat
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			allowBikeAlternateAnimations
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool allowBikeAlternateAnimations
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bHasMaxHealth
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool bHasMaxHealth
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bHasMicrophone
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool bHasMicrophone
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bHelmetHasBeenShot
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool bHelmetHasBeenShot
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			bInvincible
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool bInvincible
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			cantBeKnockedOffBike
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.int8_t cantBeKnockedOffBike
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			controlsDisabledByScript
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool controlsDisabledByScript
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			disableHelmetArmor
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool disableHelmetArmor
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			disableHomingMissileLockForVehiclePedInside
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool disableHomingMissileLockForVehiclePedInside
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			disableStartEngine
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool disableStartEngine
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			disableVehicleCombat
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool disableVehicleCombat
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			dontActivateRagdollFromExplosions
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool dontActivateRagdollFromExplosions
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			dontActivateRagdollFromVehicleImpact
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool dontActivateRagdollFromVehicleImpact
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			dontDragMeOutOfCar
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool dontDragMeOutOfCar
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			dontTakeOffHelmet
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool dontTakeOffHelmet
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			everybodyBackOff
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool everybodyBackOff
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			forceHelmetVisorSwitch
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool forceHelmetVisorSwitch
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			hasHelmet
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool hasHelmet
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			hasSetJackSpeed
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool hasSetJackSpeed
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ignoreInteriorCheckForSprinting
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool ignoreInteriorCheckForSprinting
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ignoreMeleeFistWeaponDamageMult
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool ignoreMeleeFistWeaponDamageMult
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ignoresExplosions
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool ignoresExplosions
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			inTutorial
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool inTutorial
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isAntagonisticToPlayer
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool isAntagonisticToPlayer
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isPerformingVehicleMelee
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool isPerformingVehicleMelee
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isScuba
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool isScuba
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isSpectating
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool isSpectating
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			isSwitchingHelmetVisor
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool isSwitchingHelmetVisor
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			lawOnlyAttackIfPlayerIsWanted
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool lawOnlyAttackIfPlayerIsWanted
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			lawPedsCanFleeFromNonWantedPlayer
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool lawPedsCanFleeFromNonWantedPlayer
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			myVehicleIsMyInteresting
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool myVehicleIsMyInteresting
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			neverTarget
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool neverTarget
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			newMaxHealthArmour
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool newMaxHealthArmour
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			noCriticalHits
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool noCriticalHits
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			notDamagedByBullets
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool notDamagedByBullets
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			notDamagedByCollisions
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool notDamagedByCollisions
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			notDamagedByFlames
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool notDamagedByFlames
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			notDamagedByMelee
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool notDamagedByMelee
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			notDamagedBySmoke
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool notDamagedBySmoke
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			notDamagedBySteam
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool notDamagedBySteam
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			pedIsArresting
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool pedIsArresting
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			pendingTutorialSessionChange
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool pendingTutorialSessionChange
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			playerIsWeird
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool playerIsWeird
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			playersDontDragMeOutOfCar
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool playersDontDragMeOutOfCar
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			randomPedsFlee
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool randomPedsFlee
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			respawning
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool respawning
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			swatHeliSpawnWithinLastSpottedLocation
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool swatHeliSpawnWithinLastSpottedLocation
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			treatFriendlyTargettingAndDamage
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool treatFriendlyTargettingAndDamage
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			useKinematicModeWhenStationary
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool useKinematicModeWhenStationary
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			useKinematicPhysics
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool useKinematicPhysics
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			useLockpickVehicleEntryAnimations
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool useLockpickVehicleEntryAnimations
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			useOverrideFootstepPtFx
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool useOverrideFootstepPtFx
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			willJackAnyPlayer
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool willJackAnyPlayer
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			willJackWantedPlayersRatherThanStealCar
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.bool willJackWantedPlayersRatherThanStealCar
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		Players
	</summary>
	<details style="margin-left:16px;">
		<summary>
			Get
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the players for a given filter.</p>
			<pre><code class="language-lua">table<int, int> Players.Get(ePlayerListSort filter, string search)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetByConId
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the NetGamePlayer for a given connection id.</p>
			<pre><code class="language-lua">CNetGamePlayer Players.GetByConId(int cxn)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetByEndpointId
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the NetGamePlayer for a given endpoint id.</p>
			<pre><code class="language-lua">CNetGamePlayer Players.GetByEndpointId(int ep)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetByGamerId
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the NetGamePlayer for a given gamer id.</p>
			<pre><code class="language-lua">CNetGamePlayer Players.GetByGamerId(int gamerId)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetByIP
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the NetGamePlayer for a given ip.</p>
			<pre><code class="language-lua">CNetGamePlayer Players.GetByIP(netSocketAddress addr)
CNetGamePlayer Players.GetByIP(int ip)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetById
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the NetGamePlayer for a given playerId.</p>
			<pre><code class="language-lua">CNetGamePlayer Players.GetById(int playerId)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetByPeerId
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the NetGamePlayer for a given peer id.</p>
			<pre><code class="language-lua">CNetGamePlayer Players.GetByPeerId(int peerId)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetByRockstarId
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the NetGamePlayer for a given rockstar id.</p>
			<pre><code class="language-lua">CNetGamePlayer Players.GetByRockstarId(int rid)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetCPed
		</summary>
		<div style="margin-left:16px;">
			<p>Gets the player's CPed.</p>
			<pre><code class="language-lua">CPed Players.GetCPed(int playerId)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetCam
		</summary>
		<div style="margin-left:16px;">
			<p>Gets the player's cam position.</p>
			<pre><code class="language-lua">V3 Players.GetCam(int playerId)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetCamRot
		</summary>
		<div style="margin-left:16px;">
			<p>Gets the player's cam rotation in eulers.</p>
			<pre><code class="language-lua">V3 Players.GetCamRot(int playerId)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetIP
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the player SocketAddress.</p>
			<pre><code class="language-lua">SocketAddress Players.GetIP(int playerId)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetIPInfo
		</summary>
		<div style="margin-left:16px;">
			<p>Returns info about players ip.</p>
			<pre><code class="language-lua">table<string, string> Players.GetIPInfo(int playerId)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetIPString
		</summary>
		<div style="margin-left:16px;">
			<p>Returns a readable player ip string including the type of the connection.</p>
			<pre><code class="language-lua">string Players.GetIPString(int playerId)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetName
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the player name.</p>
			<pre><code class="language-lua">string Players.GetName(int playerId)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetNetAddress
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the player NetAddress.</p>
			<pre><code class="language-lua">NetAddress Players.GetNetAddress(int playerId)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetTags
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the player tags as string.</p>
			<pre><code class="language-lua">string Players.GetTags(int playerId)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetWaypoint
		</summary>
		<div style="margin-left:16px;">
			<p>Gets if the player has a waypoint, the position of the waypoint, and the owner of the waypoint.</p>
			<pre><code class="language-lua">bool, V3, int Players.GetWaypoint(int playerId)
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		PoolMgr
	</summary>
	<details style="margin-left:16px;">
		<summary>
			GetCCamera
		</summary>
		<div style="margin-left:16px;">
			<p>Return the camera class object. Can have a performance impact if called to frequently.</p>
			<pre><code class="language-lua">CPhysical PoolMgr.GetCCamera(int index)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetCObject
		</summary>
		<div style="margin-left:16px;">
			<p>Return the object class object. Can have a performance impact if called to frequently.</p>
			<pre><code class="language-lua">CPhysical PoolMgr.GetCObject(int index)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetCPed
		</summary>
		<div style="margin-left:16px;">
			<p>Return the ped class object. Can have a performance impact if called to frequently.</p>
			<pre><code class="language-lua">CPed PoolMgr.GetCPed(int index)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetCPickup
		</summary>
		<div style="margin-left:16px;">
			<p>Return the pickup class object. Can have a performance impact if called to frequently.</p>
			<pre><code class="language-lua">CPhysical PoolMgr.GetCPickup(int index)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetCVehicle
		</summary>
		<div style="margin-left:16px;">
			<p>Return the vehicle class object. Can have a performance impact if called to frequently.</p>
			<pre><code class="language-lua">CVehicle PoolMgr.GetCVehicle(int index)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetCamera
		</summary>
		<div style="margin-left:16px;">
			<p>Return the camera handle for a specific index. Can have a performance impact if called to frequently.</p>
			<pre><code class="language-lua">int PoolMgr.GetCamera(int index)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetCurrentCameraCount
		</summary>
		<div style="margin-left:16px;">
			<p>Return the current amount of cameras.</p>
			<pre><code class="language-lua">int PoolMgr.GetCurrentCameraCount()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetCurrentObjectCount
		</summary>
		<div style="margin-left:16px;">
			<p>Return the current amount of objects.</p>
			<pre><code class="language-lua">int PoolMgr.GetCurrentObjectCount()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetCurrentPedCount
		</summary>
		<div style="margin-left:16px;">
			<p>Return the current amount of peds.</p>
			<pre><code class="language-lua">int PoolMgr.GetCurrentPedCount()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetCurrentPickupCount
		</summary>
		<div style="margin-left:16px;">
			<p>Return the current amount of pickups.</p>
			<pre><code class="language-lua">int PoolMgr.GetCurrentPickupCount()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetCurrentVehicleCount
		</summary>
		<div style="margin-left:16px;">
			<p>Return the current amount of vehicles.</p>
			<pre><code class="language-lua">int PoolMgr.GetCurrentVehicleCount()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetMaxCameraCount
		</summary>
		<div style="margin-left:16px;">
			<p>Return the maximum amount of cameras.</p>
			<pre><code class="language-lua">int PoolMgr.GetMaxCameraCount()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetMaxObjectCount
		</summary>
		<div style="margin-left:16px;">
			<p>Return the maximum amount of objects.</p>
			<pre><code class="language-lua">int PoolMgr.GetMaxObjectCount()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetMaxPedCount
		</summary>
		<div style="margin-left:16px;">
			<p>Return the maximum amount of peds.</p>
			<pre><code class="language-lua">int PoolMgr.GetMaxPedCount()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetMaxPickupCount
		</summary>
		<div style="margin-left:16px;">
			<p>Return the maximum amount of pickups.</p>
			<pre><code class="language-lua">int PoolMgr.GetMaxPickupCount()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetMaxVehicleCount
		</summary>
		<div style="margin-left:16px;">
			<p>Return the maximum amount of vehicles.</p>
			<pre><code class="language-lua">int PoolMgr.GetMaxVehicleCount()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetObject
		</summary>
		<div style="margin-left:16px;">
			<p>Return the object handle for a specific index. Can have a performance impact if called to frequently.</p>
			<pre><code class="language-lua">int PoolMgr.GetObject(int index)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetPed
		</summary>
		<div style="margin-left:16px;">
			<p>Return the ped handle for a specific index. Can have a performance impact if called to frequently.</p>
			<pre><code class="language-lua">int PoolMgr.GetPed(int index)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetPickup
		</summary>
		<div style="margin-left:16px;">
			<p>Return the pickup handle for a specific index. Can have a performance impact if called to frequently.</p>
			<pre><code class="language-lua">int PoolMgr.GetPickup(int index)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetRenderedObjects
		</summary>
		<div style="margin-left:16px;">
			<p>Return all currrently rendered CObject pointers</p>
			<pre><code class="language-lua">table<int, CObject> PoolMgr.GetRenderedObjects()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetRenderedPeds
		</summary>
		<div style="margin-left:16px;">
			<p>Return all currrently rendered CPed pointers</p>
			<pre><code class="language-lua">table<int, CPed> PoolMgr.GetRenderedPeds()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetRenderedVehicles
		</summary>
		<div style="margin-left:16px;">
			<p>Return all currrently rendered CVehicle pointers</p>
			<pre><code class="language-lua">table<int, CVehicle> PoolMgr.GetRenderedVehicles()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetVehicle
		</summary>
		<div style="margin-left:16px;">
			<p>Return the vehicle handle for a specific index. Can have a performance impact if called to frequently.</p>
			<pre><code class="language-lua">int PoolMgr.GetVehicle(int index)
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		Script
	</summary>
	<details style="margin-left:16px;">
		<summary>
			ExecuteAsScript
		</summary>
		<div style="margin-left:16px;">
			<p>Changes the current script context to your desired script, calls your function and then restores the orignal script context.</p>
			<pre><code class="language-lua">void Script.ExecuteAsScript(string scriptName, function fn)
void Script.ExecuteAsScript(int scriptHash, function fn)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			QueueJob
		</summary>
		<div style="margin-left:16px;">
			<p>Queues a function that will be exeucted in a native thread.</p>
			<pre><code class="language-lua">int Script.QueueJob(function(script, variadic_args) func, variadic_args va)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RegisterLooped
		</summary>
		<div style="margin-left:16px;">
			<p>Register a script that will be called in a loop.</p>
			<pre><code class="language-lua">int Script.RegisterLooped(function(variadic_args) func, variadic_args va)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Yield
		</summary>
		<div style="margin-left:16px;">
			<p>Sleeps for the given time in milliseconds. Should only be executed in a native thread.</p>
			<pre><code class="language-lua">void Script.Yield(int ms)
void Script.Yield()
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		ScriptGlobal
	</summary>
	<details style="margin-left:16px;">
		<summary>
			GetBool
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool ScriptGlobal.GetBool(int global)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetFloat
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number ScriptGlobal.GetFloat(int global)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetInt
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int ScriptGlobal.GetInt(int global)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetPtr
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int ScriptGlobal.GetPtr(int global)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetString
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">string ScriptGlobal.GetString(int global)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetTunableByHash
		</summary>
		<div style="margin-left:16px;">
			<p>Returns a pointer to the tunable. Returns 0 if not found.</p>
			<pre><code class="language-lua">int ScriptGlobal.GetTunableByHash(int hash)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetBool
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void ScriptGlobal.SetBool(int global, bool value)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetFloat
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void ScriptGlobal.SetFloat(int global, number value)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetInt
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void ScriptGlobal.SetInt(int global, int value)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetString
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void ScriptGlobal.SetString(int global, string text)
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		ScriptLocal
	</summary>
	<details style="margin-left:16px;">
		<summary>
			GetBool
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool ScriptLocal.GetBool(int scriptHash, int local)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetFloat
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number ScriptLocal.GetFloat(int scriptHash, int local)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetInt
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int ScriptLocal.GetInt(int scriptHash, int local)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetPtr
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int ScriptLocal.GetPtr(int scriptHash, int global)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetString
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">string ScriptLocal.GetString(int scriptHash, int local)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetBool
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void ScriptLocal.SetBool(int scriptHash, int local, bool value)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetFloat
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void ScriptLocal.SetFloat(int scriptHash, int local, number value)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetInt
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void ScriptLocal.SetInt(int scriptHash, int local, int value)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetString
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void ScriptLocal.SetString(int scriptHash, int local, string text)
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		SetShouldUnload
	</summary>

</details>
<details>
	<summary>
		ShouldUnload
	</summary>

</details>
<details>
	<summary>
		SocketAddress
	</summary>
	<details style="margin-left:16px;">
		<summary>
			IPv4
		</summary>
		<div style="margin-left:16px;">
			<p>This value is a raw 4 byte integer.</p>
			
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Port
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ToString
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">string object:ToString(bool port)
string SocketAddress.ToString(SocketAddress address, bool port)
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		Stats
	</summary>
	<details style="margin-left:16px;">
		<summary>
			GetBool
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool,int Stats.GetBool(int hash)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetFloat
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool,number Stats.GetFloat(int hash)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetInt
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool,int Stats.GetInt(int hash)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetBool
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool Stats.SetBool(int hash, int value)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetFloat
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool Stats.SetFloat(int hash, number value)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetInt
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool Stats.SetInt(int hash, int value)
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		Tab
	</summary>
	<details style="margin-left:16px;">
		<summary>
			AddFeature
		</summary>
		<div style="margin-left:16px;">
			<p>Adds a feature to the tab.</p>
			<pre><code class="language-lua">void object:AddFeature(int hash)
void object:AddFeature(int hash, int index)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AddSeperator
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">object:AddSeperator(string text)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AddSubTab
		</summary>
		<div style="margin-left:16px;">
			<p>Adds Tab Button and returns the created tab.</p>
			<pre><code class="language-lua">Tab object:AddSubTab(string text, string desc)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetContent
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">ListWidget object:GetContent(int index)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetContentSize
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the number of widgets in this tab.</p>
			<pre><code class="language-lua">int object:GetContentSize()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetDesc
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">string object:GetDesc()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetSelectedContent
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">ListWidget object:GetSelectedContent()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetSelectedContentId
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object:GetSelectedContentId()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetSubTab
		</summary>
		<div style="margin-left:16px;">
			<p>Returns a sub tab by name.</p>
			<pre><code class="language-lua">Tab object:GetSubTab(string text)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetText
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">string object:GetText()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RemoveSubTab
		</summary>
		<div style="margin-left:16px;">
			<p>Removes a sub tab and returns the amount of removed tab buttons.</p>
			<pre><code class="language-lua">int object:RemoveSubTab(Tab tab)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetDesc
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">object:SetDesc(string desc)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetSelectedContentId
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">object:SetSelectedContentId(int index)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetText
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">object:SetText(string text)
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		TaskSlotData
	</summary>
	<details style="margin-left:16px;">
		<summary>
			taskActive
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool object.taskActive
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			taskPriority
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.taskPriority
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			taskSequenceId
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.taskSequenceId
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			taskTreeDepth
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.taskTreeDepth
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			taskType
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.taskType
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		Texture
	</summary>
	<details style="margin-left:16px;">
		<summary>
			GetTexture
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">D3D11Texture Texture.GetTexture(int id)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsTextureValid
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">bool Texture.IsTextureValid(int id)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LoadTexture
		</summary>
		<div style="margin-left:16px;">
			<p>Creates a new texture that can load files such as gif,jpg,png etc.</p>
			<pre><code class="language-lua">int Texture.LoadTexture(string file)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LoadTextureAsync
		</summary>
		<div style="margin-left:16px;">
			<p>Creates a new texture that can load files such as gif,jpg,png etc.</p>
			<pre><code class="language-lua">int Texture.LoadTextureAsync(string file)
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		Time
	</summary>
	<details style="margin-left:16px;">
		<summary>
			Get
		</summary>
		<div style="margin-left:16px;">
			<p>Retrieves the current system time in seconds.</p>
			<pre><code class="language-lua">int Time.Get()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetEpoche
		</summary>
		<div style="margin-left:16px;">
			<p>Retrieves the time since Epoche in seconds.</p>
			<pre><code class="language-lua">int Time.GetEpoche()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetEpocheMs
		</summary>
		<div style="margin-left:16px;">
			<p>Retrieves the time since Epoche in milliseconds.</p>
			<pre><code class="language-lua">int Time.GetEpocheMs()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetEpocheNs
		</summary>
		<div style="margin-left:16px;">
			<p>Retrieves the time since Epoche in nanoseconds, might not equal system time.</p>
			<pre><code class="language-lua">int Time.GetEpocheNs()
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		Utils
	</summary>
	<details style="margin-left:16px;">
		<summary>
			ExecuteScript
		</summary>
		<div style="margin-left:16px;">
			<p>Executes the given script. File can be relative or absolute.</p>
			<pre><code class="language-lua">bool Utils.ExecuteScript(string file)
Utils.ExecuteScript("MyScript.lua")
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetClipBoardText
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">string Utils.GetClipBoardText()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetLastJoinedPlayer
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the last joined player id.</p>
			<pre><code class="language-lua">int Utils.GetLastJoinedPlayer()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetLastLeftPlayer
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the last joined player id.</p>
			<pre><code class="language-lua">int Utils.GetLastLeftPlayer()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetSelectedPlayer
		</summary>
		<div style="margin-left:16px;">
			<p>Returns the current selected player id.</p>
			<pre><code class="language-lua">int Utils.GetSelectedPlayer()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsKeyDown
		</summary>
		<div style="margin-left:16px;">
			<p>Check if a key is down. Use the Microsoft Virtual Key Codes.</p>
			<pre><code class="language-lua">bool Utils.IsKeyDown(int vk)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			IsKeyPressed
		</summary>
		<div style="margin-left:16px;">
			<p>Check if a key has been pressed or is hold down for longer time. Use the Microsoft Virtual Key Codes.</p>
			<pre><code class="language-lua">bool Utils.IsKeyPressed(int vk)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Joaat
		</summary>
		<div style="margin-left:16px;">
			<p>Hashes a string using joaat. Returns the hash as unsigned int.</p>
			<pre><code class="language-lua">int Utils.Joaat(string str)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			MciSendString
		</summary>
		<div style="margin-left:16px;">
			<p>The mciSendString function sends a command string to an MCI device. The device that the command is sent to is specified in the command string. For more information browse it on the internet.</p>
			<pre><code class="language-lua">bool Utils.MciSendString(string str)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PlaySound
		</summary>
		<div style="margin-left:16px;">
			<p>Can be used to play mp3 or wav files.</p>
			<pre><code class="language-lua">bool Utils.PlaySound(string str, bool looped)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetClipBoardText
		</summary>
		<div style="margin-left:16px;">
			<p>For no extra notification leave whatNotify empty.</p>
			<pre><code class="language-lua">Utils.SetClipBoardText(string text, string whatNotify)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetSelectedPlayer
		</summary>
		<div style="margin-left:16px;">
			<p>Sets the current selected Player Id. Returns the previous selected player id.</p>
			<pre><code class="language-lua">int Utils.SetSelectedPlayer(int playerId)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			StopSound
		</summary>
		<div style="margin-left:16px;">
			<p>Stops all currently played sounds.</p>
			<pre><code class="language-lua">void Utils.StopSound()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			sJoaat
		</summary>
		<div style="margin-left:16px;">
			<p>Hashes a string using joaat. Returns the hash as signed int.</p>
			<pre><code class="language-lua">int Utils.sJoaat(string str)
</code></pre>
		</div>
	</details>

</details>
<details>
	<summary>
		V2
	</summary>
	<details style="margin-left:16px;">
		<summary>
			Add
		</summary>
		<div style="margin-left:16px;">
			<p>Add a value to a V2.</p>
			<pre><code class="language-lua">V2 V2.Add(V2 vector, number value)
V2 V2.Add(V2 vector, V2 value)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Multiply
		</summary>
		<div style="margin-left:16px;">
			<p>Multiply a value with a V2.</p>
			<pre><code class="language-lua">V2 V2.Multiply(V2 vector, number value)
V2 V2.Multiply(V2 vector, V2 value)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			New
		</summary>
		<div style="margin-left:16px;">
			<p>Create a new V2 object.</p>
			<pre><code class="language-lua">V2 V2.New()
V2 V2.New(number x, number y, number z)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Subtract
		</summary>
		<div style="margin-left:16px;">
			<p>Subtract a value from a V2.</p>
			<pre><code class="language-lua">V2 V2.Subtract(V2 vector, number value)
V2 V2.Subtract(V2 vector, V2 value)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			x
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			y
		</summary>
	</details>

</details>
<details>
	<summary>
		V3
	</summary>
	<details style="margin-left:16px;">
		<summary>
			Add
		</summary>
		<div style="margin-left:16px;">
			<p>Add a value to a V3.</p>
			<pre><code class="language-lua">V3 V3.Add(V3 vector, number value)
V3 V3.Add(V3 vector, V3 value)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DirectionToRotation
		</summary>
		<div style="margin-left:16px;">
			<p>Takes a direction and returns a rotation.</p>
			<pre><code class="language-lua">V3 V3.DirectionToRotation(V3 vector)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Multiply
		</summary>
		<div style="margin-left:16px;">
			<p>Multiply a value with a V3.</p>
			<pre><code class="language-lua">V3 V3.Multiply(V3 vector, number value)
V3 V3.Multiply(V3 vector, V3 value)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			New
		</summary>
		<div style="margin-left:16px;">
			<p>Create a new V3 object.</p>
			<pre><code class="language-lua">V3 V3.New()
V3 V3.New(number x, number y, number z)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RotationToDirection
		</summary>
		<div style="margin-left:16px;">
			<p>Takes a rotation and returns a direction.</p>
			<pre><code class="language-lua">V3 V3.RotationToDirection(V3 vector)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Subtract
		</summary>
		<div style="margin-left:16px;">
			<p>Subtract a value from a V3.</p>
			<pre><code class="language-lua">V3 V3.Subtract(V3 vector, number value)
V3 V3.Subtract(V3 vector, V3 value)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			x
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			y
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			z
		</summary>
	</details>

</details>
<details>
	<summary>
		V4
	</summary>
	<details style="margin-left:16px;">
		<summary>
			New
		</summary>
		<div style="margin-left:16px;">
			<p>Create a new V4 object.</p>
			<pre><code class="language-lua">V4 V4.New()
V4 V4.New(number x, number y, number z, number w)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			w
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			x
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			y
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			z
		</summary>
	</details>

</details>
<details>
	<summary>
		eCallbackTrigger
	</summary>
	<details style="margin-left:16px;">
		<summary>
			OnNewVehicle
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			OnPlayerJoin
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			OnPlayerLeave
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			OnPlayerPedChange
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			OnPlayerPedRespawn
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			OnPostPresent
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			OnPresent
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			OnSessionChange
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			OnTick
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			OnWeaponChange
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			OnWeaponReloaded
		</summary>
	</details>

</details>
<details>
	<summary>
		eCurlCode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			CURLE_COULDNT_CONNECT
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CURLE_COULDNT_RESOLVE_HOST
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CURLE_COULDNT_RESOLVE_PROXY
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CURLE_FAILED_INIT
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CURLE_FTP_WEIRD_SERVER_REPLY
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CURLE_NOT_BUILT_IN
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CURLE_OK
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CURLE_OUT_OF_MEMORY
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CURLE_REMOTE_ACCESS_DENIED
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CURLE_UNSUPPORTED_PROTOCOL
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CURLE_URL_MALFORMAT
		</summary>
	</details>

</details>
<details>
	<summary>
		eCurlOption
	</summary>
	<details style="margin-left:16px;">
		<summary>
			CURLOPT_CUSTOMREQUEST
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CURLOPT_HTTPAUTH
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CURLOPT_NOPROGRESS
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CURLOPT_POST
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CURLOPT_POSTFIELDS
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CURLOPT_URL
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CURLOPT_USERAGENT
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CURLOPT_WRITEDATA
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CURLOPT_WRITEFUNCTION
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CURLOPT_XFERINFODATA
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CURLOPT_XFERINFOFUNCTION
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CURLOPT_XOAUTH2_BEARER
		</summary>
	</details>

</details>
<details>
	<summary>
		eEntityType
	</summary>
	<details style="margin-left:16px;">
		<summary>
			BUILDING
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			COMPOSITE
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DUMMY_OBJECT
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GRASS_INSTANCE_LIST
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			INSTANCE_LIST
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LIGHT
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			MLO
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NOTHING
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NOTINPOOLS
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			OBJECT
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PARTICLESYSTEM
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PED
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PORTAL
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TOTAL
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			VEHICLE
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			VEHICLEGLASSCOMPONENT
		</summary>
	</details>

</details>
<details>
	<summary>
		eFeatureType
	</summary>
	<details style="margin-left:16px;">
		<summary>
			Button
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Combo
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ComboToggles
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Custom
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			InputColor3
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			InputColor4
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			InputFloat
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			InputInt
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			InputText
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			List
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ListWithInfo
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SliderFloat
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SliderFloatToggle
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SliderInt
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SliderIntToggle
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			Toggle
		</summary>
	</details>

</details>
<details>
	<summary>
		eGuiMode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			Both
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ClickGUI
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ListGUI
		</summary>
	</details>

</details>
<details>
	<summary>
		eLogColor
	</summary>
	<details style="margin-left:16px;">
		<summary>
			BLUE
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BROWN
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CYAN
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DARKGRAY
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GREEN
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			INTENSIFY
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LIGHTBLUE
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LIGHTCYAN
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LIGHTGRAY
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LIGHTGREEN
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LIGHTMAGENTA
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			LIGHTRED
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			MAGENTA
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			RED
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			WHITE
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			YELLOW
		</summary>
	</details>

</details>
<details>
	<summary>
		eLuaEvent
	</summary>
	<details style="margin-left:16px;">
		<summary>
			NET_EVENT
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ON_CHAT_MESSAGE
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ON_PLAYER_JOIN
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ON_PLAYER_LEFT
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ON_PLAYER_PED_CHANGE
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ON_PLAYER_PED_RESPAWN
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ON_POST_PRESENT
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ON_PRESENT
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ON_REACTION
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ON_SESSION_CHANGE
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ON_SYNC_DATA_NODE
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ON_UNLOAD
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ON_VEHICLE_CHANGE
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ON_WEAPON_CHANGE
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ON_WEAPON_RELOADED
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SCRIPTED_GAME_EVENT
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SHOULD_COLLIDE
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SHOULD_TRIGGER_EXCLUSIVE_SYNC
		</summary>
	</details>

</details>
<details>
	<summary>
		ePlayerListSort
	</summary>
	<details style="margin-left:16px;">
		<summary>
			ALPHABETICAL
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			DISTANCE
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			HOST_QUEUE
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			PLAYER_ID
		</summary>
	</details>

</details>
<details>
	<summary>
		eProtectionType
	</summary>
	<details style="margin-left:16px;">
		<summary>
			AIMING_AT_YOU
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BAD_SCRIPT_EVENT
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CHAT_BANNED_WORD
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CHAT_SPAM
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CRASH
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			KICK
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			REPORT
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SHOOTING_AT_YOU
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			UNKNOWN
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			VOTE_KICK
		</summary>
	</details>

</details>
<details>
	<summary>
		eReportReason
	</summary>
	<details style="margin-left:16px;">
		<summary>
			CODE_TAMPERING
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CRC_CODE_CRCS
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CRC_COMPROMISED
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CRC_EXE_SIZE
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CRC_NOT_REPLIED
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CRC_REQUEST_FLOOD
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GAME_SERVER_CASH_BANK
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GAME_SERVER_CASH_WALLET
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GAME_SERVER_INVENTORY
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GAME_SERVER_SERVER_INTEGRITY
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SCRIPT_CHEAT_DETECTION
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TELEMETRY_BLOCK
		</summary>
	</details>

</details>
<details>
	<summary>
		eSyncDataNode
	</summary>
	<details style="margin-left:16px;">
		<summary>
			CAutomobileCreationDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CBikeGameStateDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CBoatGameStateDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CDoorCreationDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CDoorMovementDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CDoorScriptGameStateDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CDoorScriptInfoDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CDynamicEntityGameStateDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CEntityOrientationDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CEntityScriptGameStateDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CEntityScriptInfoDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CGlobalFlagsDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CHeliControlDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CHeliHealthDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CMigrationDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CObjectCreationDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CObjectGameStateDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CObjectOrientationNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CObjectScriptGameStateDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CObjectSectorPosNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPedAIDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPedAppearanceDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPedAttachDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPedComponentReservationDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPedCreationDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPedGameStateDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPedHealthDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPedInventoryDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPedMovementDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPedMovementGroupDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPedOrientationDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPedScriptCreationDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPedScriptGameStateDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPedSectorPosMapNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPedSectorPosNavMeshNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPedTaskSequenceDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPedTaskSpecificDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPedTaskTreeDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPhysicalAngVelocityDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPhysicalAttachDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPhysicalGameStateDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPhysicalHealthDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPhysicalMigrationDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPhysicalScriptGameStateDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPhysicalScriptMigrationDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPhysicalVelocityDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPickupCreationDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPickupPlacementCreationDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPickupPlacementStateDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPickupScriptGameStateNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPickupSectorPosNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPlaneControlDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPlaneGameStateDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPlayerAmbientModelStreamingNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPlayerAppearanceDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPlayerCameraDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPlayerCreationDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPlayerExtendedGameStateNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPlayerGameStateDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPlayerGamerDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPlayerPedGroupDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPlayerSectorPosNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CPlayerWantedAndLOSDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CSectorDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CSectorPositionDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CSubmarineControlDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CSubmarineGameStateDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CTrainGameStateDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CVehicleAngVelocityDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CVehicleAppearanceDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CVehicleComponentReservationDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CVehicleControlDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CVehicleCreationDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CVehicleDamageStatusDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CVehicleGadgetDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CVehicleGameStateDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CVehicleHealthDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CVehicleProximityMigrationDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CVehicleScriptGameStateDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CVehicleSteeringDataNode
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			CVehicleTaskDataNode
		</summary>
	</details>

</details>
<details>
	<summary>
		eToastPos
	</summary>
	<details style="margin-left:16px;">
		<summary>
			BOTTOM_LEFT
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			BOTTOM_RIGHT
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TOP_LEFT
		</summary>
	</details>
	<details style="margin-left:16px;">
		<summary>
			TOP_RIGHT
		</summary>
	</details>

</details>
<details>
	<summary>
		fwAttachmentEntityExtension
	</summary>
	<details style="margin-left:16px;">
		<summary>
			AttachChild
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">CPhysical object.AttachChild
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AttachFlags
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.AttachFlags
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AttachOffset
		</summary>
		<div style="margin-left:16px;">
			<p>This is world pos for constraints with world</p>
			<pre><code class="language-lua">V3 object.AttachOffset
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AttachParent
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">CPhysical object.AttachParent
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AttachParentOffset
		</summary>
		<div style="margin-left:16px;">
			<p>Attachment offset on parent</p>
			<pre><code class="language-lua">V3 object.AttachParentOffset
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			AttachSibling
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">CPhysical object.AttachSibling
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			GetRotation
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">number x,y,z,w object:GetRotation()
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			MyAttachBone
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.MyAttachBone
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			NoCollisionEntity
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">CPhysical object.NoCollisionEntity
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			OtherAttachBone
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">int object.OtherAttachBone
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			SetRotation
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">void object:SetRotation(number x, number y, number z, number w)
</code></pre>
		</div>
	</details>
	<details style="margin-left:16px;">
		<summary>
			ThisEntity
		</summary>
		<div style="margin-left:16px;">
			<pre><code class="language-lua">CPhysical object.ThisEntity
</code></pre>
		</div>
	</details>

</details>
