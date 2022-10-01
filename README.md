# Abilities

1. Define Ability class in Abilities folder within domain models folder
    <br> class must have constructor contain model
    <br> all functions in class is callable for ability

<img width="610" alt="image" src="https://user-images.githubusercontent.com/62018036/193430353-a7eed363-7d83-4cf1-80c2-751e53375da3.png">

2. Call (Winch\Domain\Core\Traits\ModelAbility) trait in Model

<img width="906" alt="image" src="https://user-images.githubusercontent.com/62018036/193430308-c65f0239-2fbb-4b4f-8ca3-fc212a477393.png">

3. Define protected string abilityClass property in Model

<img width="743" alt="image" src="https://user-images.githubusercontent.com/62018036/193430436-e60c0378-30aa-4f90-a90d-536540b1c887.png">

4. Usage in classes

<img width="833" alt="image" src="https://user-images.githubusercontent.com/62018036/193430459-5db82399-1ec4-41ab-a43c-c47a72964339.png">

5. Usage in views

<img width="985" alt="image" src="https://user-images.githubusercontent.com/62018036/193430476-10a24786-436f-47c1-948f-46eb3ccf97ad.png">
