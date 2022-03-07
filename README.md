### Hi there 👋 I'm Giang

### About Me
```ruby
require "readme_dsl"

class SoftwareEngineer

  working :currently do
    "Shopify"
  end

  working :previously do
    ["Nike", "Ubiquiti"]
  end

  learning do
    ["Ruby on Rails", "React", "GraphQL"]
  end

  previous_experiences do |industry|
    industry.years = "10+"
    industry.years_actual = nil
    industry.skills = ["Java", "Microservices", "AWS", "Content Management"]
  end

  personal_interests do |era|
    era.during_covid ["Video Games", "Reading", "Long Walks"]
    era.before_covid ["Video Games", "Traveling", "Long Walks on Tropical Beaches"]
  end

  currently_playing "Elden Ring"

  find_me do |at|
    at[:linkedin] = "https://www.linkedin.com/in/giangphan"
    at[:github] = "https://github.com/gphan"
    at[:website] = "https://www.giangphan.com"
  end

  pronouns do
    "he/him"
  end

end
```
