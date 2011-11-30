# Sassy
Saasy-rails a rails eninge that helps with billing, accounts, and user mangement for accounts. The idea is based off of [ThoughtBot's](http://thoughtbot.com) [Suacy](http://rubygems.org/gems/saucy) 

How To Install
---------------
1. Clone the Repo
`git clone git://github.com/Mab879/saasy-rails.git billing`

2. In your `config/routes.rb`
`mount Saasy::Engine => "/billing", :as 'billing'

