# Homebase Guides

## Submit Game for Review

All games using the Jackpot Rising platform must be approved by a member of our staff. Approve will typically occur within 24 hours of submission. Contact <support@jackpotrising.com> if you need to expedite this process.

!> The test build that you submit to Jackpot Rising for approval must be the same version (i.e 1.0 or 1.1) as the production build that you are submitting to Apple.

#### 1. Select Your Game

Select your game by tapping the **Details** button

![Screenshot](media/submit/001.png)

#### 2. Create a TEST Tournament

For detailed instructions, please see [Creating a Tournament](homebase/integration?id=create-a-tournament)

![Screenshot](media/submit/002.png)

#### 3. Submit for Approval

Once you have created a test tournament, return to the Game Details page and tap **Submit My Game.**

![Screenshot](media/submit/003.png)

#### 4. Provide Game Details

![Screenshot](media/submit/004.png)

1. Select the platform(s) that you will be submitting for the game.
2. Provide the version number and app details for the build that you are submitting.
3. For iOS: Send an invitation through Testflight to <developer@jackpotrising.com>

> Your point of contact email (set within Homebase > Account) will be notified once the approval is complete. If denied, a reason will be provided. If accepted, the game will then appear in the Jackpot Rising games library.

---

## Monitoring Tournaments

#### 1. Select Your Game

Select your game by tapping the **Details** button

![Screenshot](media/monitor/001.png)

#### 2. Select a Tournament

Find your tournament in the list of active, recurring, or archived tournaments. Then tap the **View Details** button.

![Screenshot](media/monitor/002.png)

#### 3. Review a Tournament

On this page you can view live tournament information, including the leaderboard standings (not pictured).

![Screenshot](media/monitor/003.png)

---

## Managing Account and Funds

### Manage Account Information

The Account section is where you can view and edit the details for your point of contact, studio, and payment methods.

![Screenshot](media/account/001.png)

### Deposit, Withdraw, and More

Start by tapping the **View** button on the left side of the page. 

![Screenshot](media/account/002.png)

Here you may add or withdraw funds from your account and view a transaction history and recent earnings.

![Screenshot](media/account/003.png)

---

## Custom Game Currency

In addition to real money tournaments, you may also fund and reward tournmanets with custom game currency (ex: gold coins). This allows players to purchase additional content from within your in-game shop, for example.

> Please note, you may add as many game currencies as you wish per game.

#### Add a Game Currency

Once you have [added a game](homebase/integration?id=add-a-game) within Homebase, browse to the game details, then tap the **Add New Currency** button.

![Screenshot](media/currency/001.png)

Select the **Currency** tab to provide the required resources.

![Screenshot](media/currency/002.png)

**Webhook URL**

When a tournament is completed and settled, Jackpot Rising will make an HTTP Post to the API endpoint provided. The call payload will include all relevant information needed to reward your players. This includes: ranks, player information, scores, and jackpot amount(s).

?> Contact <support@jackpotrising.com> if you require assistance with this process.

**Currency Assets**

- Currency Icon (256x256): a visual representation of your game currency
- Currency Name: a text-based representation of your game currency (ex: Gold Coins) 

**Available Game Currencies**

Previously created game currencies will be displayed here.

#### Using a Game Currency

When you [Create a Tournament](homebase/integration?id=create-a-tournament) for this game, you will now see the option to select your new game currency.

![Screenshot](media/currency/003.png)

Tournaments utilizing your in-game currency operate the same as real-money tournaments, including support for both tournament tiers and payout distribution.

![Screenshot](media/currency/004.png)

![Screenshot](media/currency/005.png)
