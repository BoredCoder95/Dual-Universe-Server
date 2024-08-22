<details>
  <summary>Character</summary>
  <blockquote>
    
    talentPointsPerSecond: 100 # 1
    defaultWallet 1000000 # 200000
    nanocrafterTimeMultiplier: 0.01 # 1.0
    calibrationGain: 1 # 0.35

  </blockquote>
</details>

<details>
  <summary>FeaturesConfig</summary>
  <blockquote>
    
talentPointsPerSecond: 100 # 1

defaultWallet 1000000 # 200000

nanocrafterTimeMultiplier: 0.01 # 1.0

calibrationGain: 1 # 0.35

  </blockquote>
</details>


# 
BaseItem
    Consumable
        Element
            ConstructElement
                IndustryInfrastructure
                    MiningUnit
                        calibrationCooldownHour: 0
                        calibrationDecreaseRatePerHour: 0
                        pickupCooldownHour: 0
                        runtimeHours: 0.1
                        
                        MiningUnitSmall1
                            newPlayerDefaultQty: 3 # 0
                Systems
                    TerritoryScannerUnit
                        TerritoriesScanner
                            duration: 30 # 900
            PlanetElement
                CoreUnit
                    CoreUnitStatic
                        CoreUnitStatic512
                            hidden: false #true
Character
    talentPointsPerSecond: 100 # 1
    defaultWallet 1000000 # 200000
    nanocrafterTimeMultiplier: 0.01 # 1.0
    calibrationGain: 1 # 0.35
FeaturesConfig
    ConstructSpeedConfig
        maxHeavyLinearSpeedKmH: 100000 # 20000
        maxLightLinearSpeedKmH: 200000 # 50000
    TerritoriesConfig
        upkeepFee: 1 # 500000
FeaturesList
    allowBaseShieldOnStaticConstruct: true
    allowIndustryOnDynamicConstruct: true
    allowMarketOnDynamicConstruct: true
Talent
    AdvancedSchematicResearchTimeEfficiency
        value: -10 # -2
    SchematicCostOptimization
        value: -10 # -5
    SchematicResearchTimeEfficiency
        value: -10 # -3
    AdvancedSchematicCostOptimization:
        value: -10 # -5




Warp Cell
    basic parts instead
