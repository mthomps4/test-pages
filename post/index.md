---
title: "POST HOME"
description: "BLAH"
---

# Index Post
adsf

```elixir
defmodule Math do
  def thing(%{asdf: 2}) do
    Enum.map([1,2,3], fn (x) -> x * 2 end)
  end
end
```

```javascript 
  export const Page = () => { 
    const url = "https://"
    return (
      <div>
        <p> { url } </p> 
      </div>
  }
```

```graphql
type Query {
  hero: Character
}

type Character {
  name: String
  friends: [Character]
  homeWorld: Planet
  species: Species
}

type Planet {
  name: String
  climate: String
}

type Species {
  name: String
  lifespan: Int
  origin: Planet
}
```

```ruby
    # Our Lion Class Inherits All the stuff from our Animal Class
    class Animal
      attr_accessor :color, :name
      def initialize ( name, color )
        @name = name
        @color = color
      end
    end
     
    class Lion < Animal		# Inherit by using < Animal 
      def speak
        return "RAWR!"
      end
    end
     
    #  Instantiate our class
    lion = Lion.new( "lion", "golden" )
     
    # Inspect
    puts lion.inspect
     
    # Speak
    puts lion.speak
     
    # Color inherited from Animal class!
    puts lion.color
```
