### Hi there 👋 I'm Giang

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
    [:ruby_on_rails, :react, :graphql]
  end

  previous_experiences do |industry|
    industry.years = "10+"
    industry.years_actual = nil
    industry.skills = [:java, :microservices, :aws, :content_management]
  end

  hobbies do |era|
    era.before_covid = [:video_games, :computers, :traveling, :beaches, :photography, :climbing, :running]
    era.during_covid = [:video_games, :computers, :reading, :long_walks]
    era.after_covid = [:video_games, :computers] + (era.before_covid + era.during_covid).sample(3)
  end

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
